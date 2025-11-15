# HLoM3.github.io

<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hugo López Miguel — CV</title>
  <meta name="description" content="CV de Hugo López Miguel: Ciencia de Datos, ML, nube, bases de datos, analítica y visualización." />
  <style>
    :root{
      --bg:#fff;
      --text:#0f172a;
      --muted:#475569;
      --accent:#0ea5e9;
      --chip:#e2e8f0;
      --card:#ffffff;
      --border:#e5e7eb;
      --max: 820px;
    }
    @media (prefers-color-scheme: dark){
      :root{
        --bg:#0b1220; --text:#e5e7eb; --muted:#a5b4fc; --chip:#111827;
        --card:#0f172a; --border:#1f2937; --accent:#38bdf8;
      }
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans";
      background:var(--bg); color:var(--text); line-height:1.6;
    }
    .wrap{max-width:var(--max); margin:0 auto; padding:28px 18px}
    header{display:flex;align-items:flex-start;justify-content:space-between;gap:16px;flex-wrap:wrap}
    h1{margin:0; font-size:clamp(28px, 4vw, 36px)}
    .subtitle{margin:.25rem 0 0 0; color:var(--muted)}
    .chips{display:flex; gap:8px; flex-wrap:wrap; margin-top:8px}
    .chip{background:var(--chip); color:var(--text); border:1px solid var(--border); border-radius:999px; padding:6px 10px; font-size:12px}
    .contacts a{display:inline-flex; gap:8px; align-items:center; color:var(--text); text-decoration:none; border:1px solid var(--border); padding:8px 12px; border-radius:10px}
    .contacts{display:flex; gap:10px; flex-wrap:wrap}
    main{margin-top:24px}
    section{background:var(--card); border:1px solid var(--border); border-radius:14px; padding:16px 18px; margin-bottom:14px}
    h2{margin:0 0 8px 0; font-size:18px; letter-spacing:.2px}
    h3{margin:.4rem 0 .2rem 0; font-size:15px}
    .row{display:grid; grid-template-columns: 1fr auto; gap:8px 12px}
    .muted{color:var(--muted)}
    ul{padding-left:18px; margin:.3rem 0 .6rem}
    .two-col{display:grid; grid-template-columns: 1fr 1fr; gap:12px}
    @media (max-width:760px){ .two-col{grid-template-columns: 1fr} .row{grid-template-columns:1fr} }
    footer{color:var(--muted); font-size:12px; text-align:center; margin-top:18px}
    a.link{color:var(--accent); text-decoration:none}
    .skill-badges{display:flex; flex-wrap:wrap; gap:8px; margin-top:6px}
    .badge{border:1px solid var(--border); border-radius:999px; padding:6px 10px; font-size:12px}
    .pill{display:inline-block; padding:2px 8px; border:1px solid var(--border); border-radius:999px; font-size:12px; color:var(--muted)}
    .spacer{height:4px}
    @media print{
      body{background:#fff}
      section, .contacts a{box-shadow:none}
      a.link{text-decoration:underline}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div>
        <h1>Hugo López Miguel</h1>
        <p class="subtitle">Estudiante de Ciencia de Datos · Machine Learning · Nube · Analítica y Visualización</p>
        <div class="chips">
          <span class="chip">Python</span>
          <span class="chip">ML</span>
          <span class="chip">ETL</span>
          <span class="chip">SQL</span>
          <span class="chip">Power BI</span>
        </div>
      </div>
      <nav class="contacts">
        <a href="tel:+525540948482" aria-label="Llamar a Hugo">📞 55 4094 8482</a>
        <a href="mailto:hugolm3001@gmail.com" aria-label="Enviar correo a Hugo">✉️ hugolm3001@gmail.com</a>
        <a href="https://www.linkedin.com/in/hugo-l%C3%B3pez-miguel-902349234" target="_blank" rel="noopener">in/ hugo-lópez-miguel</a>
        <a href="https://github.com/" target="_blank" rel="noopener">GitHub</a>
      </nav>
    </header>

    <main>
      <section id="perfil">
        <h2>Perfil</h2>
        <p>
          Soy estudiante de Ciencia de Datos con conocimientos en machine learning, cómputo en la nube,
          bases de datos y analítica/visualización. Desarrollo soluciones y análisis que facilitan la
          toma de decisiones basada en datos y abordo problemas complejos con un enfoque técnico y analítico.
        </p>
      </section>

      <section id="educacion">
        <h2>Educación</h2>
        <div class="row">
          <div>
            <h3>Instituto Politécnico Nacional — ESCOM</h3>
            <div class="muted">Licenciatura en Ciencia de Datos</div>
          </div>
          <div class="muted">ago 2020 – presente</div>
        </div>
        <div class="row">
          <div>
            <h3>Instituto Tecnológico Autónomo de México (ITAM)</h3>
            <div class="muted">Ingeniería en Computación</div>
          </div>
          <div class="muted">ago 2022 – presente</div>
        </div>
      </section>

      <section id="experiencia">
        <h2>Experiencia</h2>
        <div class="row">
          <div>
            <h3>Consecal — Prácticas profesionales</h3>
            <div class="muted">Ciudad de México</div>
            <ul>
              <li>Automatización de flujos ETL para registros de laboratorio de múltiples fuentes.</li>
              <li>Integración de datos en BD centralizada y exposición de interfaces de consulta.</li>
              <li>Adaptación de pipelines para distintos formatos y tipos de datos.</li>
            </ul>
          </div>
          <div class="muted">jul 2024 – sep 2024</div>
        </div>
      </section>

      <section id="certificaciones">
        <h2>Certificaciones</h2>
        <ul class="two-col">
          <li>Cisco CCNA: Introduction to Networks</li>
          <li>Microsoft Office Specialist — Word 2013</li>
          <li>Microsoft Office Specialist — Excel 2013</li>
          <li>Microsoft Office Specialist — PowerPoint 2013</li>
        </ul>
      </section>

      <section id="habilidades">
        <h2>Herramientas técnicas</h2>
        <div><span class="pill">Avanzado</span></div>
        <div class="skill-badges">
          <span class="badge">Pandas</span><span class="badge">NumPy</span><span class="badge">scikit-learn</span>
        </div>
        <div class="spacer"></div>
        <div><span class="pill">Intermedio</span></div>
        <div class="skill-badges">
          <span class="badge">Keras</span><span class="badge">PyTorch</span><span class="badge">SQL</span><span class="badge">Power BI</span><span class="badge">HTML</span><span class="badge">CSS</span>
        </div>
        <div class="spacer"></div>
        <div><span class="pill">Básico</span></div>
        <div class="skill-badges">
          <span class="badge">PySpark</span><span class="badge">Django</span><span class="badge">Tableau</span><span class="badge">Linux</span><span class="badge">MongoDB</span><span class="badge">Azure</span>
        </div>
        <div class="spacer"></div>
        <div><span class="pill">Lenguajes</span></div>
        <div class="skill-badges">
          <span class="badge">Python</span><span class="badge">Java</span><span class="badge">R</span>
        </div>
      </section>

      <section id="idiomas">
        <h2>Idiomas</h2>
        <ul>
          <li>Inglés: B1 (Cambridge)</li>
          <li>Español: Nativo</li>
        </ul>
      </section>
    </main>

    <footer>
      Ciudad de México · Actualizado automáticamente para web · © Hugo López Miguel
    </footer>
  </div>
</body>
</html>
