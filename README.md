# servicios-blockchain-IA
<<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Consultoría Blockchain & DeFi — Tu Nombre</title>
  <meta name="description" content="Consultoría en blockchain, criptomonedas, DeFi y contratos inteligentes. Comunidad con planes Básico, Intermedio y Avanzado; guía en ingresos pasivos (DeFi & airdrops) y soporte experto." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
  <script src="https://unpkg.com/@phosphor-icons/web"></script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background: #0b1020;
      color: #e6e9f5;
    }
    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #7c3aed, #22d3ee);
      color: white;
    }
    header h1 {
      font-family: 'Poppins', sans-serif;
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .cta {
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .btn {
      padding: 12px 20px;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s ease;
    }
    .btn-primary {
      background: #7c3aed;
      color: white;
    }
    .btn-primary:hover {
      background: #5b21b6;
    }
    .btn-ghost {
      border: 2px solid white;
      color: white;
    }
    .btn-ghost:hover {
      background: rgba(255,255,255,0.2);
    }
    main {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    section {
      margin-bottom: 60px;
    }
    h2 {
      font-family: 'Poppins', sans-serif;
      font-size: 2rem;
      color: #22d3ee;
      margin-bottom: 20px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      padding: 8px 0;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    #comunidad div {
      background: #111a34;
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 20px;
    }
    #comunidad h3 {
      margin-top: 0;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #0f162d;
      color: #a7b0c4;
    }
    a {
      color: #22d3ee;
    }
  </style>
  <style>
    :root{
      --bg:#0b1020; --bg-soft:#0f162d; --text:#e6e9f5; --muted:#a7b0c4;
      --brand:#7c3aed; --brand-2:#22d3ee; --success:#22c55e; --card:#111a34;
      --radius:16px; --shadow:0 10px 30px rgba(0,0,0,.35);
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0; font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, "Helvetica Neue", Arial; color:var(--text);
      background:
        radial-gradient(1200px 600px at 10% -10%, rgba(124,58,237,.15), transparent 60%),
        radial-gradient(1000px 600px at 90% -20%, rgba(34,211,238,.12), transparent 50%),
        var(--bg);
    }

    /* Layout */
    main{max-width:1100px; margin:0 auto; padding:0 20px}
    section{padding:56px 0}
    header{padding:84px 20px 48px; background:linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01)); border-bottom:1px solid rgba(255,255,255,.06)}
    h1{font-family:Poppins, Inter, sans-serif; font-weight:800; letter-spacing:-.3px; font-size: clamp(2rem, 5vw, 3rem); margin:12px 0}
    h2{font-family:Poppins, Inter, sans-serif; font-size: clamp(1.4rem, 3vw, 2rem); margin:0 0 18px}
    p{line-height:1.6}
    a{color:inherit}

    /* Buttons */
    .btn{display:inline-flex; align-items:center; gap:10px; border:0; border-radius:12px; padding:12px 18px; font-weight:700; cursor:pointer; text-decoration:none; transition:.2s transform, .2s opacity}
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:linear-gradient(135deg, var(--brand), var(--brand-2)); color:white; box-shadow:0 10px 25px rgba(124,58,237,.35)}
    .btn-ghost{background:transparent; color:var(--text); border:1px solid rgba(255,255,255,.15)}
    .cta{display:flex; gap:12px; flex-wrap:wrap; margin-top:16px}

    /* Servicios */
    #servicios ul{display:grid; grid-template-columns:repeat(2, minmax(0,1fr)); gap:12px 18px; padding:0; list-style:none}
    #servicios li{background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02)); border:1px solid rgba(255,255,255,.08); border-radius:14px; padding:14px 16px}
    @media (max-width:720px){#servicios ul{grid-template-columns:1fr}}

    /* Ingresos */
    #ingresos p{color:var(--muted)}

    /* Comunidad (planes) */
    #comunidad{border-top:1px solid rgba(255,255,255,.06); border-bottom:1px solid rgba(255,255,255,.06); background:rgba(255,255,255,.02)}
    #comunidad > div{display:grid; grid-template-columns:repeat(3, minmax(0,1fr)); gap:18px; max-width:1100px; margin:0 auto; padding:0 20px}
    #comunidad > div > div{background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03)); border:1px solid rgba(255,255,255,.1); border-radius:18px; padding:20px; box-shadow:var(--shadow)}
    #comunidad h3{margin-top:4px}
    @media (max-width:900px){#comunidad > div{grid-template-columns:1fr 1fr}}
    @media (max-width:620px){#comunidad > div{grid-template-columns:1fr}}

    /* Contacto */
    #contacto p{margin:6px 0}

    /* Footer */
    footer{padding:36px 20px; border-top:1px solid rgba(255,255,255,.06); color:var(--muted); text-align:center; background:rgba(0,0,0,.2)}
  </style>
</head>
<body>
  <header>
    <h1>Consultoría Blockchain & DeFi</h1>
    <p>Asesoría en integración blockchain, contratos inteligentes y estrategias DeFi.</p>
    <div class="cta">
      <a class="btn btn-primary" href="https://wa.me/573104106551?text=Hola%2C%20quiero%20informaci%C3%B3n%20de%20consultor%C3%ADa%20Blockchain%20%26%20DeFi" target="_blank"><i class="ph ph-whatsapp-logo"></i> WhatsApp Business</a>
      <a class="btn btn-ghost" href="https://wa.me/573122615844?text=Hola%2C%20me%20gustar%C3%ADa%20hablar%20contigo%20sobre%20consultor%C3%ADa" target="_blank"><i class="ph ph-user"></i> Contacto profesional</a>
    </div>
  </header>

  <main>
    <section id="servicios">
      <h2>Servicios</h2>
      <ul>
        <li>Consultoría en adopción blockchain y tokenización</li>
        <li>Diseño, pruebas y revisión de smart contracts (Solidity)</li>
        <li>Estrategia DeFi: liquidez, staking, airdrops y gobernanza</li>
        <li>Integraciones Web3 (WalletConnect, ethers.js) y seguridad básica</li>
      </ul>
    </section>

    <section id="ingresos">
      <h2>Ingresos Pasivos (DeFi & Airdrops)</h2>
      <p>Metodología para identificar oportunidades reales y minimizar riesgos.</p>
    </section>

    <section id="comunidad">
      <h2>Planes de la Comunidad</h2>
      <div>
        <h3>Básico — US$15/mes</h3>
        <a class="btn btn-primary" href="https://wa.me/573104106551?text=Quiero%20unirme%20al%20plan%20B%C3%A1sico%20de%20la%20comunidad" target="_blank">Unirme</a>
      </div>
      <div>
        <h3>Intermedio — US$39/mes</h3>
        <a class="btn btn-primary" href="https://wa.me/573104106551?text=Quiero%20unirme%20al%20plan%20Intermedio%20de%20la%20comunidad" target="_blank">Unirme</a>
      </div>
      <div>
        <h3>Avanzado — US$79/mes</h3>
        <a class="btn btn-primary" href="https://wa.me/573104106551?text=Quiero%20unirme%20al%20plan%20Avanzado%20de%20la%20comunidad" target="_blank">Unirme</a>
      </div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p><i class="ph ph-whatsapp-logo"></i> <a href="https://wa.me/573104106551" target="_blank">+57 310 410 6551</a> — Business</p>
      <p><i class="ph ph-whatsapp-logo"></i> <a href="https://wa.me/573122615844" target="_blank">+57 312 261 5844</a> — Profesional</p>
      <p><i class="ph ph-envelope"></i> <a href="mailto:nftcryptolab2030@gmail.com">nftcryptolab2030@gmail.com</a></p>
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Todos los derechos reservados</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
