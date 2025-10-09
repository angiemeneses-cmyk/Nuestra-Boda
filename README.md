# Nuestra-Boda
Boda
<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Invitación de Boda — Ana & José</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
<style>
:root{
--bg:#fffaf6;
--accent:#7b3f98;
--muted:#8c8c8c;
--card:#ffffff;
--shadow:0 6px 18px rgba(18,18,18,0.08);
}
*{box-sizing:border-box}
body{font-family:Inter,system-ui,Arial,sans-serif;background:linear-gradient(180deg,var(--bg),#fff);margin:0;color:#222}
.container{max-width:980px;margin:36px auto;padding:24px}


/* Hero */
.hero{display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:center}
.card{background:var(--card);border-radius:16px;padding:28px;box-shadow:var(--shadow)}
.names{font-family:'Playfair Display',serif;font-size:38px;color:var(--accent);margin:0}
.subtitle{color:var(--muted);margin:8px 0 18px}
.details{display:flex;gap:14px;flex-wrap:wrap}
.detail{background:#f9f6fb;padding:10px 14px;border-radius:10px;font-size:14px}


/* Image */
.photo{height:360px;border-radius:16px;background:url('https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=9fd5a2d0a5b2b0b7b1e2b0f3a7c3b9c9') center/cover;border:4px solid rgba(255,255,255,0.75)}


/* Sections */
.grid-2{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
.section h3{margin-top:0;font-family:'Playfair Display',serif}
.rsvp label{display:block;font-size:14px;margin:10px 0 4px}
input[type=text],input[type=email],select,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #ececec;font-size:14px}
button.primary{background:var(--accent);color:white;padding:12px 18px;border-radius:10px;border:0;font-weight:600;cursor:pointer}
button.ghost{background:transparent;border:1px solid #eee;padding:10px;border-radius:10px;cursor:pointer}


/* Footer */
footer{text-align:center;color:var(--muted);margin-top:28px;font-size:14px}


/* Responsive */
@media (max-width:880px){
.hero{grid-template-columns:1fr;}
.grid-2{grid-template-columns:1fr}
.photo{height:260px}
}


/* small animations */
.fade{opacity:0;transform:translateY(8px);transition:all .6s ease}
.fade.in{opacity:1;transform:none}


.details .icon{display:inline-block;margin-right:8px;vertical-align:middle}


</style>
</head>
<body>
<div class="container">
<header class="hero card fade" id="hero">
<div>
<p style="margin:0;color:var(--muted)">Con mucha ilusión</p>
<h1 class="names">Ana María & José Alejandro</h1>
<p class="subtitle">Nos casamos el <strong>12 de Abril de 2026</strong> — Acompáñanos a celebrar</p>


<div class="details">
<div class="detail"><span class="icon">📍</span> Hacienda La Esperanza, El Tambo, Cauca</div>
<div class="detail"><span class="icon">🕒</span> Ceremonia 3:00 PM — Recepción 5:00 PM</div>
<div class="detail"><span class="icon">🎟️</span> Formal / Confirmar asistencia</div>
</div>


<p style="margin-top:18px;color:#444;line-height:1.5">Queremos compartir este día especial con las personas que nos han acompañado en el camino. Tu presencia es el mejor regalo. Si no puedes venir, envíanos un mensaje — ¡te sentiremos cerca!</p>
</html>
