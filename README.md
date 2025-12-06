<div align="center">
  <!-- Simple glass banner using SVG (inline, safe) -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" style="border-radius:14px;">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="#0f1724"/>
        <stop offset="0.45" stop-color="#071026"/>
        <stop offset="1" stop-color="#0b0f1a"/>
      </linearGradient>
      <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="36" />
      </filter>
    </defs>

    <!-- soft neon blobs (blurred group) -->
    <g filter="url(#blur)" opacity="0.12">
      <circle cx="160" cy="50" r="110" fill="#083d63"/>
      <circle cx="430" cy="120" r="90" fill="#5b1f6b" opacity="0.9"/>
      <circle cx="920" cy="50" r="130" fill="#083d63" opacity="0.95"/>
    </g>

    <!-- glass panel -->
    <rect x="12" y="12" rx="14" ry="14" width="1176" height="196" fill="url(#g)" opacity="0.96" />
    <rect x="12" y="12" rx="14" ry="14" width="1176" height="196" fill="white" opacity="0.02" style="mix-blend-mode:overlay"/>

    <!-- title -->
    <text x="60" y="78" fill="#ffffff" font-size="30" font-family="Inter, Arial" font-weight="700">Raihan Ahmad</text>
    <text x="60" y="104" fill="#9fb0c8" font-size="14" font-family="Inter, Arial">Full-Stack Developer · React · FastAPI · Node.js</text>

    <!-- neon underline -->
    <rect x="60" y="112" width="420" height="2" fill="#1E90FF" opacity="0.88"/>
  </svg>

  <!-- avatar overlay (keeps visual balance) -->
  <div style="margin-top:-56px; display:flex; justify-content:center;">
    <div style="background: rgba(255,255,255,0.03); border-radius:12px; padding:10px; backdrop-filter: blur(6px); box-shadow: 0 12px 40px rgba(0,0,0,0.6);">
      <img src="https://github.com/raihanahmadkhan.png" width="96" height="96" style="border-radius:12px; border:2px solid rgba(255,255,255,0.04)"/>
    </div>
  </div>
</div>

<!-- small divider -->
<div style="height:20px; margin-top:6px;">
  <svg viewBox="0 0 1200 28" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M0,12 C300,40 900,-8 1200,12 L1200 28 L0 28 Z" fill="#06070a"/>
  </svg>
</div>

<div align="center" style="max-width:1000px; margin:auto; padding:10px 12px;">

  <!-- Intro row -->
  <div style="display:flex; gap:18px; align-items:flex-start; justify-content:space-between; flex-wrap:wrap;">
    <!-- Left -->
    <div style="flex:1; min-width:300px; background:linear-gradient(135deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:12px; padding:18px; box-shadow: 0 10px 30px rgba(0,0,0,0.6);">
      <h2 style="margin:0;color:#e6eef8;">Hello — I'm Raihan 👋</h2>
      <p style="color:#9fb0c8; line-height:1.45; margin-top:8px;">
        Full-Stack Developer building modern, user-centered web applications and APIs using <strong>React</strong>, <strong>FastAPI</strong>, and <strong>Node.js</strong>.
        I focus on clean UX, dependable backend systems, and deployable solutions (Docker / PostgreSQL / AWS).
      </p>

      <div style="display:flex; gap:8px; margin-top:12px; flex-wrap:wrap;">
        <a href="mailto:raihanhzb@gmail.com" style="text-decoration:none;">
          <img alt="email" src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=flat-square" />
        </a>
        <a href="https://linkedin.com/in/raihanahmadkhan" style="text-decoration:none;">
          <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square" />
        </a>
        <a href="https://github.com/raihanahmadkhan" style="text-decoration:none;">
          <img alt="github" src="https://img.shields.io/badge/GitHub-000000?logo=github&logoColor=white&style=flat-square" />
        </a>
      </div>

      <p style="color:#9fb0c8; font-size:13px; margin-top:12px;">
        Quick highlights — React · FastAPI · Node.js · PostgreSQL · Docker · AWS · Competitive programming
      </p>
    </div>

    <!-- Right -->
    <div style="width:340px; min-width:260px; background: linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01)); border-radius:12px; padding:16px; box-shadow: 0 10px 30px rgba(0,0,0,0.6);">
      <h3 style="color:#e6eef8; margin:0 0 8px 0;">Tech Stack</h3>
      <div style="display:flex; flex-wrap:wrap; gap:8px;">
        <img alt="React" src="https://skillicons.dev/icons?i=react" height="36" />
        <img alt="FastAPI" src="https://skillicons.dev/icons?i=fastapi" height="36" />
        <img alt="Node.js" src="https://skillicons.dev/icons?i=nodejs" height="36" />
        <img alt="Python" src="https://skillicons.dev/icons?i=python" height="36" />
        <img alt="Postgres" src="https://skillicons.dev/icons?i=postgres" height="36" />
        <img alt="Docker" src="https://skillicons.dev/icons?i=docker" height="36" />
        <img alt="Tailwind" src="https://skillicons.dev/icons?i=tailwind" height="36" />
        <img alt="Git" src="https://skillicons.dev/icons?i=git" height="36" />
      </div>

      <!-- subtle indicator (no external CSS) -->
      <div style="margin-top:12px; display:flex; gap:10px; align-items:center;">
        <div style="width:10px; height:10px; border-radius:50%; background:linear-gradient(45deg,#6ee7b7,#3b82f6); box-shadow:0 0 10px rgba(59,130,246,0.35);"></div>
        <div style="color:#9fb0c8; font-size:13px;">Open to opportunities • Building side projects • Learning daily</div>
      </div>
    </div>
  </div>

  <!-- Stats row -->
  <div style="display:flex; gap:14px; margin-top:22px; flex-wrap:wrap; justify-content:center;">
    <!-- GitHub -->
    <div style="background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:300px; box-shadow:0 8px 24px rgba(0,0,0,0.5);">
      <h4 style="margin:6px 0 10px 0; color:#e6eef8;">GitHub</h4>
      <img src="https://github-readme-stats.vercel.app/api?username=raihanahmadkhan&show_icons=true&theme=dark&border_radius=12" alt="GitHub Stats" style="border-radius:8px;" />
      <div style="height:8px"></div>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=raihanahmadkhan&theme=dark" alt="Streak" style="border-radius:8px;" />
    </div>

    <!-- LeetCode -->
    <div style="background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:300px; box-shadow:0 8px 24px rgba(0,0,0,0.5);">
      <h4 style="margin:6px 0 10px 0; color:#e6eef8;">LeetCode</h4>
      <img src="https://leetcard.jacoblin.cool/raihanahmad?theme=dark&font=Inter&ext=contest" alt="LeetCode Card" style="border-radius:10px;" />
      <p style="color:#9fb0c8; font-size:13px; margin-top:8px;">Profile: <a href="https://leetcode.com/u/raihanahmad/" style="color:#8ab4ff">raihanahmad</a></p>
    </div>

    <!-- Codeforces -->
    <div style="background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:300px; box-shadow:0 8px 24px rgba(0,0,0,0.5);">
      <h4 style="margin:6px 0 10px 0; color:#e6eef8;">Codeforces</h4>
      <img src="https://codeforces-readme-stats.vercel.app/api/card?username=raihan_ahmad&theme=dark" alt="Codeforces Card" style="border-radius:10px;" />
      <p style="color:#9fb0c8; font-size:13px; margin-top:8px;">Profile: <a href="https://codeforces.com/profile/raihan_ahmad" style="color:#8ab4ff">raihan_ahmad</a></p>
    </div>
  </div>

  <!-- Featured projects -->
  <div style="margin-top:28px; display:flex; gap:16px; flex-wrap:wrap; justify-content:center;">
    <div style="flex:1; min-width:320px; max-width:760px; background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01)); border-radius:12px; padding:16px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
      <h3 style="color:#e6eef8; margin:0 0 8px 0;">Featured Projects</h3>

      <div style="display:flex; gap:12px; align-items:flex-start; margin-top:10px;">
        <div style="min-width:56px; height:56px; border-radius:10px; background:linear-gradient(135deg,#0b1220,#111827); display:flex; align-items:center; justify-content:center;">
          <img src="https://skillicons.dev/icons?i=react" height="32" alt="react"/>
        </div>
        <div>
          <h4 style="margin:0; color:#e6eef8;">PodcastMini</h4>
          <p style="color:#9fb0c8; margin:4px 0 0 0; font-size:13px;">
            In-browser AI podcast summarizer using client-side Transformers — privacy-first, TTS, transcript summarization.
          </p>
        </div>
      </div>

      <div style="display:flex; gap:12px; align-items:flex-start; margin-top:12px;">
        <div style="min-width:56px; height:56px; border-radius:10px; background:linear-gradient(135deg,#0b1220,#111827); display:flex; align-items:center; justify-content:center;">
          <img src="https://skillicons.dev/icons?i=python" height="32" alt="python"/>
        </div>
        <div>
          <h4 style="margin:0; color:#e6eef8;">AI Student Stress Detector</h4>
          <p style="color:#9fb0c8; margin:4px 0 0 0; font-size:13px;">
            React + FastAPI app using a Mamdani Fuzzy Inference Model with realtime charts and offline inference fallback.
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- footer / resume credit -->
  <div style="margin-top:22px; text-align:center; color:#9fb0c8; font-size:13px;">
    <div style="max-width:820px; margin:auto; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.01)); padding:12px; border-radius:10px;">
      <strong style="color:#e6eef8;">Resume</strong> — summarized content used from your uploaded resume. :contentReference[oaicite:1]{index=1}
      <div style="height:8px"></div>
      <a href="https://github.com/raihanahmadkhan" style="text-decoration:none;">
        <img src="https://img.shields.io/badge/See%20my%20work-on-GitHub-181717?logo=github&style=flat-square" alt="See my work"/>
      </a>
    </div>
  </div>

  <p style="color:#7d8a98; font-size:12px; text-align:center; margin-top:12px;">
    Note: badges and stat cards come from third-party services. If a card fails to load, try reloading later or swap with a different badge provider.
  </p>
</div>
