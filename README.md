<!--
  Black Glassmorphism — Profile README for Raihan Ahmad
  Paste this into: github.com/raihanahmadkhan/raihanahmadkhan/README.md
-->

<!-- HEADER: Glassmorphism banner + avatar -->
<div align="center">
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" style="border-radius:16px;">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="#0f1724"/>
        <stop offset="0.45" stop-color="#071026"/>
        <stop offset="1" stop-color="#0b0f1a"/>
      </linearGradient>
      <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="40" />
      </filter>
    </defs>

    <!-- soft neon blobs -->
    <g filter="url(#blur)">
      <circle cx="180" cy="60" r="120" fill="#0b3b61" opacity="0.20"/>
      <circle cx="420" cy="120" r="100" fill="#5b1f6b" opacity="0.10"/>
      <circle cx="900" cy="60" r="140" fill="#0b3b61" opacity="0.14"/>
    </g>

    <!-- glass panel -->
    <rect x="16" y="16" rx="16" ry="16" width="1168" height="188" fill="url(#g)" opacity="0.96" />
    <rect x="16" y="16" rx="16" ry="16" width="1168" height="188" fill="white" opacity="0.02" style="mix-blend-mode:overlay"/>

    <!-- title -->
    <text x="60" y="80" fill="#ffffff" font-size="34" font-family="Inter, Arial" font-weight="700">Raihan Ahmad</text>
    <text x="60" y="112" fill="#9fb0c8" font-size="16" font-family="Inter, Arial">Full-Stack Developer • React · FastAPI · Node.js</text>

    <!-- neon underline -->
    <rect x="60" y="122" width="420" height="2" fill="#1E90FF" opacity="0.9"/>
  </svg>

  <!-- avatar, small glass card overlay -->
  <div style="margin-top:-64px; display:flex; justify-content:center;">
    <div style="background: rgba(255,255,255,0.03); border-radius:16px; padding:12px; backdrop-filter: blur(6px); box-shadow: 0 8px 30px rgba(2,6,23,0.6);">
      <img src="https://github.com/raihanahmadkhan.png" width="96" height="96" style="border-radius:12px; border:2px solid rgba(255,255,255,0.06)"/>
    </div>
  </div>
</div>

<!-- WAVE divider -->
<div style="height:28px; margin-top:-6px;">
  <svg viewBox="0 0 1200 28" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M0,12 C300,40 900,-8 1200,12 L1200 28 L0 28 Z" fill="#06070a"/>
  </svg>
</div>

<!-- MAIN CONTENT -->
<div align="center" style="max-width:1000px; margin:auto;">

<!-- INTRO + CTA -->
<div style="margin-top:8px; display:flex; gap:18px; align-items:flex-start; justify-content:space-between; flex-wrap:wrap;">

  <!-- LEFT: Summary card -->
  <div style="flex:1; min-width:310px; background:linear-gradient(135deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:14px; padding:20px; box-shadow: 0 10px 30px rgba(2,6,23,0.6); backdrop-filter: blur(8px);">
    <h2 style="margin:0;color:#e6eef8;">Hello — I'm Raihan 👋</h2>
    <p style="color:#9fb0c8; line-height:1.5; margin-top:8px;">
      Full-Stack Developer building modern, user-centered web applications and APIs using <strong>React</strong>, <strong>FastAPI</strong>, and <strong>Node.js</strong>.
      I focus on clean UX, reliable backend design, and scalable deployments (Docker / PostgreSQL / AWS).
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
      Quick highlights — React, FastAPI, Node.js • PostgreSQL, MongoDB • Docker, AWS • Competitive programming.
    </p>
  </div>

  <!-- RIGHT: Skills + small animations -->
  <div style="width:360px; min-width:260px; background: linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01)); border-radius:14px; padding:18px; box-shadow: 0 10px 30px rgba(2,6,23,0.6); backdrop-filter: blur(8px);">
    <h3 style="color:#e6eef8; margin:0 0 8px 0;">Tech Stack</h3>
    <div style="display:flex; flex-wrap:wrap; gap:8px;">
      <!-- use skillicons + shields -->
      <img alt="React" src="https://skillicons.dev/icons?i=react" height="36" />
      <img alt="fastapi" src="https://skillicons.dev/icons?i=fastapi" height="36" />
      <img alt="node" src="https://skillicons.dev/icons?i=nodejs" height="36" />
      <img alt="python" src="https://skillicons.dev/icons?i=python" height="36" />
      <img alt="postgres" src="https://skillicons.dev/icons?i=postgres" height="36" />
      <img alt="docker" src="https://skillicons.dev/icons?i=docker" height="36" />
      <img alt="tailwind" src="https://skillicons.dev/icons?i=tailwind" height="36" />
      <img alt="git" src="https://skillicons.dev/icons?i=git" height="36" />
    </div>

    <!-- subtle animated indicator -->
    <div style="margin-top:12px; display:flex; gap:10px; align-items:center;">
      <div style="width:10px; height:10px; border-radius:50%; background:linear-gradient(45deg,#6ee7b7,#3b82f6); animation: pulse 1.6s infinite;"></div>
      <div style="color:#9fb0c8; font-size:13px;">Open to opportunities • Building side projects • Always learning</div>
    </div>

    <style>
      @keyframes pulse {
        0% { transform: scale(0.75); opacity: .6; }
        50% { transform: scale(1.2); opacity: 1; }
        100% { transform: scale(0.75); opacity: .6; }
      }
    </style>
  </div>
</div>

<!-- WAVE -->
<div style="margin-top:18px;">
  <svg viewBox="0 0 1200 100" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M0,40 C200,10 400,90 600,60 C800,30 1000,70 1200,40 L1200 100 L0 100 Z" fill="#06070a" opacity="0.95" />
  </svg>
</div>

<!-- STATS ROW (GitHub, LeetCode, Codeforces) -->
<div style="display:flex; gap:16px; margin-top:22px; flex-wrap:wrap; justify-content:center;">

  <!-- GitHub Stats -->
  <div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:320px; box-shadow:0 8px 24px rgba(2,6,23,0.5);">
    <h4 style="margin:6px 0 10px 0; color:#e6eef8;">GitHub</h4>
    <img src="https://github-readme-stats.vercel.app/api?username=raihanahmadkhan&show_icons=true&theme=dark&border_radius=12" alt="GitHub Stats" />
    <div style="height:10px"></div>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=raihanahmadkhan&theme=dark" alt="GitHub Streak" style="border-radius:10px;" />
  </div>

  <!-- LeetCode Card -->
  <div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:320px; box-shadow:0 8px 24px rgba(2,6,23,0.5);">
    <h4 style="margin:6px 0 10px 0; color:#e6eef8;">LeetCode</h4>
    <!-- LeetCode card generator: insert your username below -->
    <img src="https://leetcard.jacoblin.cool/raihanahmad?theme=dark&font=Inter&ext=contest" alt="LeetCode Card" style="border-radius:12px;" />
    <p style="color:#9fb0c8; font-size:13px; margin-top:8px;">Profile: <a href="https://leetcode.com/u/raihanahmad/" style="color:#8ab4ff">raihanahmad</a></p>
  </div>

  <!-- Codeforces Card -->
  <div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:12px; padding:12px; min-width:320px; box-shadow:0 8px 24px rgba(2,6,23,0.5);">
    <h4 style="margin:6px 0 10px 0; color:#e6eef8;">Codeforces</h4>
    <!-- Codeforces card (third-party service) -->
    <img src="https://codeforces-readme-stats.vercel.app/api/card?username=raihan_ahmad&theme=dark" alt="Codeforces Card" style="border-radius:12px;" />
    <p style="color:#9fb0c8; font-size:13px; margin-top:8px;">Profile: <a href="https://codeforces.com/profile/raihan_ahmad" style="color:#8ab4ff">raihan_ahmad</a></p>
  </div>

</div>

<!-- FEATURED PROJECTS -->
<div style="margin-top:28px; display:flex; gap:16px; flex-wrap:wrap; justify-content:center;">
  <div style="flex:1; min-width:320px; max-width:720px; background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01)); border-radius:12px; padding:18px; box-shadow: 0 10px 30px rgba(2,6,23,0.5);">
    <h3 style="color:#e6eef8; margin:0 0 8px 0;">Featured Projects</h3>

    <!-- Project: PodcastMini -->
    <div style="display:flex; gap:12px; align-items:flex-start; margin-top:10px;">
      <div style="min-width:64px; height:64px; border-radius:12px; background:linear-gradient(135deg,#111827,#0b1220); display:flex; align-items:center; justify-content:center; box-shadow: inset 0 -6px 18px rgba(2,6,23,0.6);">
        <img src="https://skillicons.dev/icons?i=react" height="36" alt="react"/>
      </div>
      <div>
        <h4 style="margin:0; color:#e6eef8;">PodcastMini</h4>
        <p style="color:#9fb0c8; margin:4px 0 0 0; font-size:13px;">
          Browser-first AI podcast summarizer (client-side Transformers). Private by default — in-browser transcript summarization + TTS.
        </p>
      </div>
    </div>

    <!-- Project: AI Student Stress Detector -->
    <div style="display:flex; gap:12px; align-items:flex-start; margin-top:12px;">
      <div style="min-width:64px; height:64px; border-radius:12px; background:linear-gradient(135deg,#111827,#0b1220); display:flex; align-items:center; justify-content:center;">
        <img src="https://skillicons.dev/icons?i=python" height="36" alt="python"/>
      </div>
      <div>
        <h4 style="margin:0; color:#e6eef8;">AI-Powered Student Stress Detector</h4>
        <p style="color:#9fb0c8; margin:4px 0 0 0; font-size:13px;">
          React + FastAPI app using a Mamdani Fuzzy Inference Model, realtime charts, and offline inference fallback.
        </p>
      </div>
    </div>

    <!-- more projects can be added here -->
  </div>
</div>

<!-- FOOTER: resume notice + CTA -->
<div style="margin-top:22px; text-align:center; color:#9fb0c8; font-size:13px;">
  <div style="max-width:820px; margin:auto; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.01)); padding:14px; border-radius:12px;">
    <strong style="color:#e6eef8;">Resume</strong> — summarized content used from your uploaded resume. :contentReference[oaicite:1]{index=1}
    <div style="height:8px"></div>
    <a href="https://github.com/raihanahmadkhan" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/See%20my%20work-on-GitHub-181717?logo=github&style=flat-square" alt="See my work"/>
    </a>
  </div>
</div>

<!-- small script-note -->
<p style="color:#7d8a98; font-size:12px; text-align:center; margin-top:12px;">
  Note: Some cards (LeetCode / Codeforces / GitHub stats) are generated by third-party badge services. If an image fails to load, check the service availability or replace with your preferred badges.
</p>
