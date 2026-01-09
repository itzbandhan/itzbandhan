<style>
  :root{
    --bg1:#0b1220;
    --bg2:#0f172a;
    --card:#0b1220cc;
    --border:#1f2a44;
    --text:#e5e7eb;
    --muted:#9ca3af;
    --accent:#38BDF8;
    --accent2:#6366F1;
  }

  .bp-wrap{max-width:980px;margin:0 auto;padding:10px 0;font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial;}
  .bp-hero{
    border:1px solid var(--border);
    border-radius:22px;
    padding:28px 20px;
    background:
      radial-gradient(1200px 500px at 10% 0%, rgba(56,189,248,.25), transparent 60%),
      radial-gradient(900px 500px at 90% 10%, rgba(99,102,241,.25), transparent 55%),
      linear-gradient(180deg, rgba(15,23,42,.75), rgba(11,18,32,.75));
    box-shadow: 0 12px 30px rgba(0,0,0,.25);
    overflow:hidden;
    position:relative;
  }
  .bp-hero:before{
    content:"";
    position:absolute; inset:-2px;
    background: linear-gradient(90deg, rgba(56,189,248,.35), rgba(99,102,241,.35), rgba(56,189,248,.35));
    filter: blur(22px);
    opacity:.35;
    z-index:0;
  }
  .bp-hero > *{position:relative; z-index:1;}
  .bp-title{
    margin:0;
    font-size:38px;
    line-height:1.1;
    letter-spacing:-.02em;
    color:var(--text);
  }
  .bp-title span{
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    -webkit-background-clip:text; background-clip:text; color:transparent;
  }
  .bp-sub{margin:10px 0 0;color:var(--muted);font-size:15px}
  .bp-row{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-top:16px}
  .bp-pill{
    display:inline-flex;align-items:center;gap:8px;
    padding:8px 12px;border-radius:999px;
    border:1px solid var(--border);
    background: rgba(2,6,23,.35);
    color:var(--text);
    font-size:13px;
  }
  .bp-pill b{color:var(--accent)}
  .bp-grid{display:grid;grid-template-columns: 1.1fr .9fr;gap:14px;margin-top:14px}
  @media (max-width: 860px){ .bp-grid{grid-template-columns:1fr;} .bp-title{font-size:32px} }

  .bp-card{
    border:1px solid var(--border);
    border-radius:18px;
    padding:16px;
    background: linear-gradient(180deg, rgba(15,23,42,.65), rgba(11,18,32,.65));
    box-shadow: 0 10px 24px rgba(0,0,0,.18);
  }
  .bp-h{
    display:flex;align-items:center;justify-content:space-between;gap:10px;margin:0 0 8px;
    color:var(--text); font-size:16px;
  }
  .bp-h small{color:var(--muted);font-weight:500}
  .bp-list{margin:0;padding-left:18px;color:var(--muted);line-height:1.65}
  .bp-list b{color:var(--text)}
  .bp-links{display:flex;flex-wrap:wrap;gap:10px;margin-top:10px}
  .bp-btn{
    display:inline-flex;align-items:center;gap:8px;
    padding:10px 12px;border-radius:14px;
    border:1px solid var(--border);
    background: rgba(2,6,23,.35);
    text-decoration:none !important;
    color:var(--text) !important;
    font-weight:600;font-size:13px;
    transition: transform .15s ease, border-color .15s ease;
  }
  .bp-btn:hover{transform: translateY(-1px); border-color: rgba(56,189,248,.55);}
  .bp-tagrow{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
  .bp-tag{
    font-size:12px;color:var(--muted);
    padding:6px 10px;border-radius:999px;
    border:1px solid var(--border);
    background: rgba(2,6,23,.35);
  }
  .bp-divider{height:1px;background: rgba(31,42,68,.65);margin:14px 0;}
  .bp-center{text-align:center}
  .bp-muted{color:var(--muted)}
</style>

<div class="bp-wrap">

  <div class="bp-hero" align="center">
    <h1 class="bp-title">Hey 👋, I'm <span>Bandhan Pokhrel</span></h1>
    <p class="bp-sub">Frontend Developer • UI Enthusiast • Tech Explorer</p>

    <div class="bp-row">
      <span class="bp-pill">📍 <b>Kathmandu</b>, Nepal</span>
      <span class="bp-pill">🌱 Learning <b>React</b>, <b>Next.js</b> & <b>MERN</b></span>
      <span class="bp-pill">📫 <b>codewithbandhan@gmail.com</b></span>
      <span class="bp-pill">🌐 <a href="https://itzbandhan.tech" style="color:inherit;text-decoration:none;"><b>itzbandhan.tech</b></a></span>
    </div>

    <div class="bp-row" style="margin-top:12px;">
      <img src="https://komarev.com/ghpvc/?username=itzbandhan&label=Profile%20Views&color=38BDF8&style=flat" alt="profile views" />
      <img src="https://img.shields.io/badge/Focus-Frontend%20%26%20UI-38BDF8?style=flat" alt="focus" />
      <img src="https://img.shields.io/badge/Open%20to-Collabs-6366F1?style=flat" alt="collabs" />
    </div>
  </div>

  <div class="bp-grid">

    <div class="bp-card">
      <h3 class="bp-h">🚀 About Me <small>what I do</small></h3>
      <ul class="bp-list">
        <li>Building <b>modern web UIs</b> with clean components & responsive layouts.</li>
        <li>Exploring <b>UI/UX</b> and design systems to make products feel premium.</li>
        <li>Writing blogs at <b><a href="https://blogsbandhan.blogspot.com/" style="color:var(--accent);text-decoration:none;">blogsbandhan.blogspot.com</a></b></li>
        <li>Ask me about <b>front-end development</b>, Tailwind, React patterns.</li>
        <li>Fun fact: I like breaking things to understand how they work 😄</li>
      </ul>

      <div class="bp-divider"></div>

      <h3 class="bp-h">🔗 Quick Links <small>projects & info</small></h3>
      <div class="bp-links">
        <a class="bp-btn" href="https://github.com/itzbandhan?tab=repositories">🧩 Projects</a>
        <a class="bp-btn" href="https://itzbandhan.tech">🌐 Portfolio</a>
        <a class="bp-btn" href="https://blogsbandhan.blogspot.com/">✍️ Blogs</a>
      </div>
    </div>

    <div class="bp-card">
      <h3 class="bp-h">🛠 Tech Stack <small>tools I use</small></h3>

      <div class="bp-tagrow">
        <span class="bp-tag">HTML</span>
        <span class="bp-tag">CSS</span>
        <span class="bp-tag">JavaScript</span>
        <span class="bp-tag">React</span>
        <span class="bp-tag">Next.js</span>
        <span class="bp-tag">Tailwind</span>
        <span class="bp-tag">Sass</span>
        <span class="bp-tag">Bootstrap</span>
        <span class="bp-tag">Git</span>
        <span class="bp-tag">Firebase</span>
        <span class="bp-tag">GCP</span>
        <span class="bp-tag">Arduino</span>
        <span class="bp-tag">Figma</span>
        <span class="bp-tag">Photoshop</span>
        <span class="bp-tag">Illustrator</span>
      </div>

      <div class="bp-divider"></div>

      <h3 class="bp-h">🌐 Connect <small>let's talk</small></h3>
      <div class="bp-links">
        <a class="bp-btn" href="https://linkedin.com/in/bandhanpokhrel">in LinkedIn</a>
        <a class="bp-btn" href="https://twitter.com/itzbandhan">𝕏 Twitter</a>
        <a class="bp-btn" href="https://instagram.com/_bandhann">📷 Instagram</a>
        <a class="bp-btn" href="https://dev.to/bandhan">DEV</a>
        <a class="bp-btn" href="https://codepen.io/bandhanpokhrel">CodePen</a>
        <a class="bp-btn" href="https://www.youtube.com/c/itzbandhan">▶ YouTube</a>
        <a class="bp-btn" href="https://www.leetcode.com/bandhann">⚡ LeetCode</a>
        <a class="bp-btn" href="https://discord.gg/2VKCpUp3mv">💬 Discord</a>
      </div>
    </div>

  </div>

  <div class="bp-card" style="margin-top:14px;">
    <h3 class="bp-h">☕ Support My Work <small>if you like what I build</small></h3>
    <p class="bp-muted" style="margin:0 0 10px;">Your support helps me keep building and shipping more projects.</p>
    <p align="center" style="margin:0;">
      <a href="https://www.buymeacoffee.com/bandhanpokhrel">
        <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="45" />
      </a>
      &nbsp;&nbsp;
      <a href="https://ko-fi.com/bandhanpokhrel">
        <img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="45" />
      </a>
    </p>
  </div>

  <p class="bp-center bp-muted" style="margin:14px 0 0;">
    <b style="color:var(--text);">✨ Thanks for visiting!</b> Let’s build something amazing together.
  </p>

</div>
