<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sanjay Mahesh — Resume</title>
  <meta name="description" content="Resume of Sanjay Mahesh" />

  <!-- Google font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0f1724; /* dark navy */
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#06b6d4; /* teal-ish */
      --glass: rgba(255,255,255,0.03);
      --max-width:900px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%;}
    body{
      margin:0;
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,#071021 0%, #071422 60%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px 16px;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .container{
      width:100%;
      max-width:var(--max-width);
      display:grid;
      grid-template-columns: 300px 1fr;
      gap:28px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      padding:28px;
      border-radius:12px;
      box-shadow: 0 8px 30px rgba(2,6,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }

    /* Left column */
    .sidebar{
      padding:18px;
      border-radius:10px;
      background:var(--card);
      min-height:260px;
      display:flex;
      flex-direction:column;
      gap:16px;
    }
    .avatar{
      width:100%;
      display:flex;
      gap:12px;
      align-items:center;
    }
    .photo{
      width:72px;height:72px;border-radius:12px;background:linear-gradient(180deg,var(--accent),#3b82f6);display:flex;align-items:center;justify-content:center;font-weight:700;color:#021022;font-size:20px
    }
    h1{margin:0;font-size:20px}
    h2{margin:0;font-size:14px;color:var(--muted)}

    .muted{color:var(--muted);font-size:13px}
    .section-title{font-weight:700;font-size:13px;color:var(--accent);text-transform:uppercase;letter-spacing:1px;margin-top:6px}

    .side-list{display:flex;flex-direction:column;gap:10px}
    .pill{background:var(--glass);padding:8px;border-radius:8px;font-size:13px}

    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:rgba(255,255,255,0.03);padding:6px 8px;border-radius:8px;font-size:13px}

    /* Main column */
    .main{
      padding:18px;
      border-radius:10px;
      background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.005));
    }
    .headline{display:flex;justify-content:space-between;align-items:start;gap:12px}
    .summary{color:var(--muted);margin-top:8px;font-size:14px;line-height:1.5}

    .job{margin-top:16px}
    .job h3{margin:0;font-size:15px}
    .job .meta{color:var(--muted);font-size:13px;margin-top:4px}
    .job ul{margin:10px 0 0 18px}

    .education{display:flex;flex-direction:column;gap:12px}

    footer{margin-top:18px;color:var(--muted);font-size:13px}

    /* Print-friendly */
    @media print{
      body{background:white;color:black}
      .container{box-shadow:none;border:none;background:transparent}
      a[href]:after{content:""}
    }

    /* Responsive */
    @media (max-width:820px){
      .container{grid-template-columns:1fr;}
    }

    /* controls */
    .controls{display:flex;gap:8px;align-items:center}
    .btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:inherit;cursor:pointer;font-weight:600}
  </style>
</head>
<body>
  <div class="container" id="resume">
    <aside class="sidebar">
      <div class="avatar">
        <div class="photo">SM</div>
        <div>
          <h1>Sanjay Mahesh</h1>
          <h2>Full Stack Developer</h2>
          <div class="muted">Based in India · Open to work</div>
        </div>
      </div>

      <div>
        <div class="section-title">Contact</div>
        <div class="side-list">
          <div class="pill">📧 sanjay@example.com</div>
          <div class="pill">📱 +91 98xxxxxxxx</div>
          <div class="pill">🔗 github.com/your-username</div>
        </div>
      </div>

      <div>
        <div class="section-title">Skills</div>
        <div class="skills">
          <div class="skill">HTML &amp; CSS</div>
          <div class="skill">JavaScript</div>
          <div class="skill">React</div>
          <div class="skill">Node.js</div>
          <div class="skill">Express</div>
          <div class="skill">SQL</div>
          <div class="skill">Git</div>
        </div>
      </div>

      <div>
        <div class="section-title">Languages</div>
        <div class="side-list">
          <div class="pill">English — Professional</div>
          <div class="pill">Hindi — Native</div>
          <div class="pill">Tamil — Conversational</div>
        </div>
      </div>

      <div style="margin-top:auto">
        <div class="section-title">Education</div>
        <div class="education">
          <div>
            <div style="font-weight:700">Bachelor of Computer Science</div>
            <div class="muted">College Name · 2020 — 2024</div>
          </div>
        </div>
      </div>
    </aside>

    <main class="main">
      <div class="headline">
        <div>
          <div style="font-size:20px;font-weight:800">Summary</div>
          <div class="summary">Full-stack developer with experience building responsive web apps using React, Node.js, and modern tooling. Strong problem-solver who writes maintainable code and enjoys learning new tech. Seeking roles focused on web engineering and product-driven teams.</div>
        </div>
        <div class="controls">
          <button class="btn" onclick="downloadPDF()">Download PDF</button>
          <button class="btn" onclick="print()">Print</button>
        </div>
      </div>

      <section class="job">
        <h3>Experience</h3>
        <div class="muted">Most recent first</div>

        <article style="margin-top:12px">
          <div style="display:flex;justify-content:space-between;align-items:start">
            <div>
              <div style="font-weight:700">Frontend Developer — Company ABC</div>
              <div class="muted">June 2024 — Present · Remote</div>
            </div>
            <div class="muted">Tech: React, TypeScript, Tailwind, Vite</div>
          </div>
          <ul>
            <li>Built and maintained a component library used across 6 products, improving consistency and developer speed.</li>
            <li>Reduced bundle size by 18% and improved Lighthouse performance score by optimizing images and splitting code.</li>
          </ul>
        </article>

        <article style="margin-top:12px">
          <div style="display:flex;justify-content:space-between;align-items:start">
            <div>
              <div style="font-weight:700">Junior Full Stack — Startup XYZ</div>
              <div class="muted">Aug 2022 — May 2024 · Chennai, IN</div>
            </div>
            <div class="muted">Tech: Node, Express, React</div>
          </div>
          <ul>
            <li>Implemented REST APIs and worked on authentication & payments integrations.</li>
            <li>Worked closely with designers to ship features and fixed critical bugs under tight deadlines.</li>
          </ul>
        </article>
      </section>

      <section class="job">
        <h3>Projects</h3>
        <div class="muted">Selected open-source & personal</div>
        <ul style="margin-top:8px">
          <li><strong>Project Name</strong> — Brief: small description. <span class="muted">(github.com/your-username/project)</span></li>
          <li><strong>Portfolio</strong> — Personal portfolio site built with React and Vite. <span class="muted">(github.com/your-username/portfolio)</span></li>
        </ul>
      </section>

      <section style="margin-top:16px">
        <h3>Certificates &amp; Achievements</h3>
        <ul class="muted" style="margin-top:8px">
          <li>Example: Completed Full Stack Web Development Nanodegree — 2023</li>
        </ul>
      </section>

      <footer>
        Tip: update contact info, projects and dates. To host this resume on GitHub Pages, push this file as <code>index.html</code> to a repository and enable Pages in repo settings.
      </footer>
    </main>
  </div>

  <script>
    // Small helper to download the visible resume as a PDF using the print dialog trick.
    function downloadPDF(){
      // Open a new window with the resume content and trigger print (user chooses Save as PDF)
      const content = document.getElementById('resume').outerHTML;
      const newWin = window.open('', '_blank', 'width=900,height=700');
      newWin.document.write('<!doctype html><html><head><meta charset="utf-8"><title>Resume</title>');
      newWin.document.write('<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">');
      newWin.document.write('<style>body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica Neue,Arial;color:#111;background:#fff;padding:20px} .container{max-width:900px;margin:0 auto}</style>');
      newWin.document.write('</head><body>');
      newWin.document.write(content);
      newWin.document.write('</body></html>');
      newWin.document.close();
      setTimeout(()=>{newWin.print();},600);
    }
  </script>
</body>
</html>
