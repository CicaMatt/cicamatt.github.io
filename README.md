<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Matteo Cicalese – Backend Software Engineer</title>
  <meta name="description" content="Portfolio e curriculum di Matteo Cicalese, Backend Software Engineer. Esperienze, studi, progetti, pubblicazioni e competenze." />
  <meta name="theme-color" content="#0a0a0a" />
  <!-- Open Graph -->
  <meta property="og:title" content="Matteo Cicalese – Backend Software Engineer" />
  <meta property="og:description" content="Esperienze, studi, progetti, pubblicazioni e contatti." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://YOURUSERNAME.github.io/" />
  
  <style>
    :root{
      --bg: #ffffff;
      --fg: #0b0b0b;
      --muted: #6b7280;
      --card: #f7f7f7;
      --accent: #0b72ff;
      --ring: rgba(11,114,255,.25);
      --border: #e5e7eb;
      --shadow: 0 1px 2px rgba(0,0,0,.04), 0 8px 24px rgba(0,0,0,.06);
    }
    @media (prefers-color-scheme: dark){
      :root{
        --bg: #0b0b0b;
        --fg: #f3f4f6;
        --muted: #9aa0aa;
        --card: #121212;
        --accent: #60a5fa;
        --ring: rgba(96,165,250,.35);
        --border: #1f2937;
        --shadow: 0 1px 2px rgba(0,0,0,.25), 0 8px 24px rgba(0,0,0,.35);
      }
    }

    /* Base */
    *,*::before,*::after{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background:var(--bg); color:var(--fg); line-height:1.6;
      -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;
    }
    img{max-width:100%; height:auto; display:block}
    a{color:inherit}
    a:hover{color:var(--accent)}

    /* Typography */
    :where(h1,h2,h3,h4){line-height:1.25}
    :where(h1){font-size:clamp(1.6rem, 2.2vw + 1rem, 2.4rem); margin:.25rem 0}
    :where(h2){font-size:clamp(1.15rem, 1.1vw + .9rem, 1.5rem); margin:1.75rem 0 1rem}
    :where(h3){font-size:1.05rem; margin:1rem 0 .5rem}
    p, li{max-width:75ch}
    ul{padding-left:1.2rem}

    /* Layout */
    .container{max-width:960px; margin:0 auto; padding:1.25rem}
    header{
      position:sticky; top:0; backdrop-filter:saturate(180%) blur(8px);
      background: var(--bg); /* removed color-mix for wider support */
      border-bottom:1px solid var(--border);
      z-index:10;
    }
    .nav{display:flex; gap:.75rem; align-items:center; justify-content:space-between; padding:.6rem 0}
    .brand{display:flex; align-items:center; gap:.75rem}
    .avatar{width:44px; height:44px; border-radius:50%; background:var(--card); display:inline-block; border:1px solid var(--border)}
    .name{font-weight:700; letter-spacing:.2px}
    .role{color:var(--muted); font-size:.95rem}
    nav a{color:var(--muted); text-decoration:none; padding:.4rem .6rem; border-radius:.6rem;}
    nav a:hover, nav a:focus{color:var(--fg); outline:2px solid var(--ring)}

    main{padding-top:1rem}

    .grid{display:grid; gap:1rem}
    @media(min-width:800px){ .grid{grid-template-columns: 2fr 1fr; gap:1.25rem} }

    .card{background:var(--card); border:1px solid var(--border); border-radius:1rem; padding:1rem; box-shadow:var(--shadow)}
    .list{display:grid; gap:.75rem}
    .item{display:grid; gap:.25rem}
    .meta{color:var(--muted); font-size:.95rem}

    .tags{display:flex; flex-wrap:wrap; gap:.4rem}
    .tag{font-size:.85rem; padding:.25rem .55rem; border-radius:999px; background:transparent; border:1px dashed var(--border)}

    .pill{display:inline-flex; align-items:center; gap:.5rem; padding:.5rem .75rem; border:1px solid var(--border); border-radius:.75rem; text-decoration:none; color:inherit; box-shadow:var(--shadow)}
    .pill:hover{border-color:var(--fg)}

    .footer{margin:3rem 0 2rem; color:var(--muted); font-size:.95rem}

    .section-nav{display:flex; flex-wrap:wrap; gap:.4rem}
    .section-nav a{border:1px solid var(--border); border-radius:.6rem; padding:.35rem .6rem; color:var(--muted); text-decoration:none}
    .section-nav a:hover{color:var(--fg)}

    /* Anchor offset for sticky header */
    :target{scroll-margin-top:80px}
    section[id]{scroll-margin-top:80px}

    /* Long words wrap better on mobile */
    *{word-wrap:break-word; overflow-wrap:break-word}

    /* Print */
    @media print{
      header, .section-nav, .actions, .footer{display:none}
      .card{border:0; background:transparent; padding:0; box-shadow:none}
      body{background:white; color:black}
    }
  </style>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Matteo Cicalese",
    "jobTitle": "Backend Software Engineer",
    "email": "mailto:matteocicalese01@gmail.com",
    "telephone": "+39 392 813 9527",
    "address": {"@type": "PostalAddress", "addressLocality": "Nocera Inferiore (SA)", "addressCountry": "IT"},
    "url": "",
    "sameAs": [
      "https://www.linkedin.com/in/cicamatt/",
      "https://github.com/cicamatt"
    ]
  }
  </script>
</head>
<body>
  <a class="sr-only" href="#inizio">Salta al contenuto</a>
  <header>
    <div class="container nav">
      <div class="brand">
        <span class="avatar" aria-hidden="true"></span>
        <div>
          <div class="name">Matteo Cicalese</div>
          <div class="role">Backend Software Engineer</div>
        </div>
      </div>
      <nav aria-label="Sezioni">
        <a href="#esperienze">Esperienze</a>
        <a href="#studi">Studi</a>
        <a href="#progetti">Progetti</a>
        <a href="#pubblicazioni">Pubblicazioni</a>
        <a href="#competenze">Competenze</a>
        <a href="#contatti">Contatti</a>
      </nav>
    </div>
  </header>

  <main id="inizio" class="container">
    <section class="card">
      <h1>Matteo Cicalese</h1>
      <p class="meta">Nocera Inferiore (SA) · Disponibile per viaggi e trasferte</p>
      <div class="actions" style="display:flex; gap:.5rem; flex-wrap:wrap; margin-top:.75rem">
        <a class="pill" href="mailto:matteocicalese01@gmail.com">📧 Email</a>
        <a class="pill" href="tel:+393928139527">📞 Chiama</a>
        <a class="pill" href="https://www.linkedin.com/in/cicamatt/" target="_blank" rel="noopener">in LinkedIn</a>
        <a class="pill" href="https://github.com/cicamatt" target="_blank" rel="noopener">GitHub</a>
        <a class="pill" href="Curriculum.pdf" download>⬇️ Scarica CV (PDF)</a>
      </div>
      <div class="section-nav" style="margin-top:.75rem">
        <a href="#esperienze">Esperienze</a><a href="#studi">Studi</a><a href="#progetti">Progetti</a>
        <a href="#pubblicazioni">Pubblicazioni</a><a href="#competenze">Competenze</a><a href="#contatti">Contatti</a>
      </div>
    </section>

    <div class="grid">
      <section id="esperienze" class="card" aria-labelledby="esperienze-h">
        <h2 id="esperienze-h">Esperienze</h2>
        <div class="list">
          <div class="item">
            <h3>Assegnista di Ricerca · Università degli Studi di Salerno</h3>
            <div class="meta">Gennaio 2025 – Ottobre 2025</div>
            <ul>
              <li><strong>Smartitude</strong> — Sicurezza di smart contracts e affidabilità di tool di detection</li>
              <li><strong>QualAI</strong> — Impatto del prompt engineering sulla sicurezza delle interazioni con LLM</li>
            </ul>
          </div>
        </div>
      </section>

      <aside class="card">
        <h2>Competenze chiave</h2>
        <div class="tags" aria-label="Hard skill">
          <span class="tag">Python</span>
          <span class="tag">Java</span>
          <span class="tag">SQL</span>
          <span class="tag">MongoDB</span>
          <span class="tag">HTML/CSS</span>
          <span class="tag">JavaScript</span>
          <span class="tag">C</span>
          <span class="tag">C#</span>
          <span class="tag">LaTeX</span>
          <span class="tag">Docker</span>
          <span class="tag">Git</span>
          <span class="tag">Node.js</span>
          <span class="tag">React</span>
          <span class="tag">Linux</span>
        </div>
        <h3 style="margin-top:1rem">Soft skill</h3>
        <p class="meta">Teamwork · Flessibilità · Autonomia · Persistenza · Determinazione · Empatia</p>
      </aside>
    </div>

    <section id="studi" class="card" aria-labelledby="studi-h">
      <h2 id="studi-h">Titoli di studio</h2>
      <div class="list">
        <div class="item">
          <h3>Laurea Magistrale in Informatica <span class="meta">(110 e lode)</span></h3>
          <div class="meta">Software Engineering & IT Management · Settembre 2022 – Ottobre 2024 · Università degli Studi di Salerno</div>
          <p><strong>Tesi:</strong> Definizione e valutazione di un catalogo di template di prompt engineering per la sicurezza e la qualità del codice generato da LLM.</p>
          <p class="meta">Competenze: Ingegneria del software, gestione progetti, cybersecurity, AI & Machine Learning</p>
        </div>
        <div class="item">
          <h3>Laurea Triennale in Informatica <span class="meta">(110 e lode)</span></h3>
          <div class="meta">Settembre 2019 – Settembre 2022 · Università degli Studi di Salerno</div>
          <p><strong>Tesi:</strong> Implementazione di un sistema di intrusion detection per l’IoT tramite Machine Learning.</p>
          <p class="meta">Competenze: Programmazione procedurale e OO, Fondamenti di AI, Web/Mobile/Distribuita</p>
        </div>
      </div>
    </section>

    <section id="progetti" class="card" aria-labelledby="progetti-h">
      <h2 id="progetti-h">Progetti</h2>
      <div class="list">
        <div class="item">
          <h3>Medicare · Project Manager</h3>
          <div class="meta">Python · 2023</div>
          <p>Piattaforma web per la prenotazione di visite mediche presso strutture pubbliche/ private, gestione cartella clinica ed esplorazione catalogo farmaci.</p>
        </div>
        <div class="item">
          <h3>Sentry</h3>
          <div class="meta">Python · 2022</div>
          <p>Pipeline custom di Machine Learning per classificare vulnerabilità (CVE) nei commit GitHub tramite metriche di sviluppo software.</p>
        </div>
        <div class="item">
          <h3>Quantumoonlight</h3>
          <div class="meta">Python · 2021</div>
          <p>Piattaforma web per validazione, preprocessing e classificazione dataset con pipeline personalizzabile, sfruttando backend quantistici IBM.</p>
        </div>
      </div>
    </section>

    <section id="pubblicazioni" class="card" aria-labelledby="pubblicazioni-h">
      <h2 id="pubblicazioni-h">Pubblicazioni</h2>
      <ul>
        <li>
          <span>Automated Vulnerability Injection in Solidity Smart Contracts: A Mutation‑Based Approach for Benchmark Development</span>
          <span class="meta">— EASE 2025</span>
        </li>
        <li>
          <span>Quantumoonlight: A Low‑Code Platform to Experiment with Quantum Machine Learning</span>
          <span class="meta">— ICSME 2022 Tool Demonstration Track · SoftwareX 2023</span>
          · <a href="https://www.sciencedirect.com/science/article/pii/S235271102300095X" target="_blank" rel="noopener">doi</a>
        </li>
      </ul>
    </section>

    <section id="competenze" class="card" aria-labelledby="competenze-h">
      <h2 id="competenze-h">Competenze</h2>
      <div class="grid" style="grid-template-columns:1fr 1fr">
        <div>
          <h3>Programmazione</h3>
          <ul>
            <li><strong>Proficient:</strong> Python, Java, SQL, MongoDB, HTML/CSS</li>
            <li><strong>Experienced:</strong> JavaScript, C, C#, LaTeX</li>
            <li><strong>Familiar:</strong> Java EE, PHP, Solidity, C++, Assembly, Shell</li>
          </ul>
          <h3>Librerie & Framework</h3>
          <p class="meta">jQuery, Node.js, React</p>
          <h3>Tool</h3>
          <p class="meta">Git, Docker, WordPress</p>
        </div>
        <div>
          <h3>Sistemi Operativi</h3>
          <p class="meta">Windows · Linux · macOS</p>
          <h3>Lingue</h3>
          <ul>
            <li>Italiano — Madrelingua</li>
            <li>Inglese — B2 (Cambridge)</li>
          </ul>
          <h3>Certificazioni</h3>
          <p class="meta">Richi Entrepreneurs 2023 · SEIUNISA Innovator 2023 · RobotCup Participation 2019</p>
        </div>
      </div>
    </section>

    <section id="contatti" class="card" aria-labelledby="contatti-h">
      <h2 id="contatti-h">Contatti</h2>
      <p>
        <a class="pill" href="mailto:matteocicalese01@gmail.com">matteocicalese01@gmail.com</a>
        <a class="pill" href="tel:+393928139527">+39 392 813 9527</a>
        <a class="pill" href="https://maps.app.goo.gl/pCSZWt5eJbz3mRFs9" target="_blank" rel="noopener">Nocera Inferiore (SA)</a>
      </p>
      <p class="meta">Autorizzo il trattamento dei dati personali contenuti nel mio CV ai sensi del D.Lgs. 196/2003 e del Regolamento UE 2016/679.</p>
    </section>

    <p class="footer">© <span id="year"></span> Matteo Cicalese. Minimal site · costruito con HTML/CSS.
      <a href="#inizio" class="meta" style="margin-left:.5rem">Torna su ↑</a>
    </p>
  </main>

  <script>
    // anno corrente
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
