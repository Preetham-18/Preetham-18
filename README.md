<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Preetham K P - data analytics engineer in the making.">
  <title>Preetham K P | GitHub Profile</title>
  <style>
    :root { --ink:#18211d; --muted:#68736d; --paper:#f4f6f0; --panel:#fff; --line:#dfe5dc; --green:#177245; --lime:#c9e86a; --orange:#e78745; --shadow:0 18px 50px rgba(24,33,29,.08); }
    * { box-sizing:border-box; }
    html { scroll-behavior:smooth; }
    body { margin:0; color:var(--ink); background:var(--paper); font-family:Georgia,"Times New Roman",serif; line-height:1.5; }
    a { color:inherit; }
    .shell { width:min(1120px,calc(100% - 40px)); margin:0 auto; }
    .topbar { display:flex; align-items:center; justify-content:space-between; padding:24px 0; font:700 12px/1 "Courier New",monospace; letter-spacing:.1em; text-transform:uppercase; }
    .brand { text-decoration:none; } .brand span { color:var(--green); }
    nav { display:flex; gap:24px; color:var(--muted); } nav a { text-decoration:none; } nav a:hover { color:var(--green); }
    .hero { position:relative; overflow:hidden; display:grid; grid-template-columns:1.2fr .8fr; gap:48px; align-items:end; padding:78px 0 86px; border-top:1px solid var(--line); }
    .hero::after { content:""; position:absolute; width:280px; height:280px; right:2%; top:30px; border:1px solid rgba(23,114,69,.25); border-radius:50%; box-shadow:0 0 0 24px rgba(23,114,69,.04),0 0 0 48px rgba(23,114,69,.035); pointer-events:none; }
    .eyebrow { margin:0 0 18px; color:var(--green); font:700 12px/1.2 "Courier New",monospace; letter-spacing:.13em; text-transform:uppercase; }
    h1 { max-width:700px; margin:0; font-size:clamp(48px,8vw,92px); line-height:.92; letter-spacing:-.055em; font-weight:700; } h1 em { color:var(--orange); font-style:normal; }
    .intro { max-width:560px; margin:26px 0 0; color:var(--muted); font-size:19px; }
    .hero-side { position:relative; z-index:1; padding-bottom:6px; }
    .profile-line { display:flex; align-items:center; gap:14px; margin-bottom:22px; font:700 14px/1.3 "Courier New",monospace; }
    .avatar { width:56px; height:56px; border:3px solid var(--lime); border-radius:50%; background:var(--ink); } .avatar img { width:100%; height:100%; border-radius:50%; display:block; }
    .handle { color:var(--muted); font-size:12px; font-weight:400; }
    .actions { display:flex; flex-wrap:wrap; gap:10px; }
    .button { display:inline-flex; align-items:center; gap:8px; padding:12px 17px; border:1px solid var(--ink); border-radius:3px; background:var(--ink); color:#fff; font:700 12px "Courier New",monospace; text-decoration:none; }
    .button.secondary { background:transparent; color:var(--ink); } .button:hover { transform:translateY(-2px); }
    .section { padding:58px 0; border-top:1px solid var(--line); }
    .section-heading { display:flex; align-items:baseline; justify-content:space-between; gap:20px; margin-bottom:26px; }
    h2 { margin:0; font-size:31px; letter-spacing:-.04em; } .section-heading p { margin:0; color:var(--muted); font:12px "Courier New",monospace; }
    .metrics { display:grid; grid-template-columns:repeat(4,1fr); gap:12px; } .metric,.panel,.repo { background:var(--panel); border:1px solid var(--line); box-shadow:var(--shadow); }
    .metric { padding:22px; } .metric strong { display:block; color:var(--green); font:700 32px "Courier New",monospace; } .metric span { color:var(--muted); font:11px "Courier New",monospace; text-transform:uppercase; letter-spacing:.08em; }
    .content-grid { display:grid; grid-template-columns:.85fr 1.15fr; gap:18px; } .panel { padding:28px; } .panel h3 { margin:0 0 20px; font-size:23px; } .panel p { color:var(--muted); }
    .stack { display:flex; flex-wrap:wrap; gap:8px; margin-top:22px; } .tag { padding:7px 10px; background:#eef4e9; color:var(--green); font:700 11px "Courier New",monospace; }
    .roadmap { display:grid; gap:15px; margin:0; padding:0; list-style:none; } .roadmap li { display:grid; grid-template-columns:34px 1fr auto; gap:12px; align-items:center; padding-bottom:15px; border-bottom:1px solid var(--line); } .roadmap li:last-child { padding-bottom:0; border-bottom:0; }
    .step { color:var(--orange); font:700 12px "Courier New",monospace; } .roadmap small { color:var(--muted); font:11px "Courier New",monospace; } .roadmap .current strong { color:var(--green); }
    .repo-grid { display:grid; grid-template-columns:repeat(2,1fr); gap:14px; } .repo { display:flex; flex-direction:column; min-height:180px; padding:22px; text-decoration:none; transition:transform .2s ease,border-color .2s ease; } .repo:hover { transform:translateY(-4px); border-color:var(--green); }
    .repo-title { display:flex; justify-content:space-between; gap:10px; min-width:0; overflow-wrap:anywhere; font:700 16px "Courier New",monospace; } .repo-title span { color:var(--green); } .repo p { flex:1; margin:15px 0; color:var(--muted); font-size:15px; } .repo-meta { display:flex; gap:15px; color:var(--muted); font:11px "Courier New",monospace; }
    .dot { display:inline-block; width:8px; height:8px; margin-right:5px; border-radius:50%; background:var(--orange); } footer { padding:28px 0 42px; color:var(--muted); font:12px "Courier New",monospace; }
    @media (max-width:760px) { .shell { width:min(100% - 28px,600px); } nav { display:none; } .hero { grid-template-columns:1fr; gap:30px; padding:58px 0 62px; } .hero::after { right:-110px; top:40px; } .metrics,.content-grid,.repo-grid { grid-template-columns:1fr; } .section { padding:42px 0; } .section-heading { display:block; } .section-heading p { margin-top:8px; } }
  </style>
</head>
<body>
  <header class="shell topbar"><a class="brand" href="https://github.com/Preetham-18">preetham<span>/</span>github</a><nav aria-label="Page navigation"><a href="#work">Work</a><a href="#roadmap">Roadmap</a><a href="#contact">Contact</a></nav></header>
  <main class="shell">
    <section class="hero"><div><p class="eyebrow">B.E. AIML · VTU '23-'27 · Belagavi, India</p><h1>Building a sharper view of <em>data.</em></h1><p class="intro">I'm Preetham K P, a data analytics engineer in the making. I turn a Python and machine learning foundation into useful analysis, clear dashboards, and projects worth sharing.</p></div><div class="hero-side"><div class="profile-line"><div class="avatar"><img src="https://github.com/Preetham-18.png?size=128" alt="Preetham K P"></div><div>PREETHAM K P<br><span class="handle">@Preetham-18</span></div></div><div class="actions"><a class="button" href="https://github.com/Preetham-18">View GitHub <span>↗</span></a><a class="button secondary" href="https://my-portfolio-584e.vercel.app">Portfolio <span>↗</span></a></div></div></section>
    <section class="section" aria-labelledby="snapshot-title"><div class="section-heading"><h2 id="snapshot-title">The snapshot</h2><p>LIVE FROM GITHUB / PREETHAM-18</p></div><div class="metrics"><div class="metric"><strong id="repos">--</strong><span>Public repositories</span></div><div class="metric"><strong id="followers">--</strong><span>Followers</span></div><div class="metric"><strong id="following">--</strong><span>Following</span></div><div class="metric"><strong id="joined">2023</strong><span>Joined GitHub</span></div></div></section>
    <section class="section" id="roadmap" aria-labelledby="roadmap-title"><div class="content-grid"><div class="panel"><h3 id="roadmap-title">Where I'm heading</h3><p>One deliberate step at a time: stronger fundamentals, more useful projects, and a portfolio that shows the thinking behind the result.</p><div class="stack"><span class="tag">SQL</span><span class="tag">Excel</span><span class="tag">Power BI</span><span class="tag">Python</span><span class="tag">Pandas</span><span class="tag">Git</span></div></div><div class="panel"><h3>Current roadmap</h3><ol class="roadmap"><li class="current"><span class="step">01</span><strong>SQL + Excel</strong><small>IN PROGRESS</small></li><li><span class="step">02</span><strong>Power BI / Tableau</strong><small>NEXT UP</small></li><li><span class="step">03</span><strong>Statistics for analysts</strong><small>PLANNED</small></li><li><span class="step">04</span><strong>End-to-end projects</strong><small>PLANNED</small></li></ol></div></div></section>
    <section class="section" id="work" aria-labelledby="work-title"><div class="section-heading"><h2 id="work-title">Selected repositories</h2><p id="repo-note">LOADING RECENT WORK...</p></div><div class="repo-grid" id="repo-grid"><div class="repo"><div class="repo-title">Fetching repositories...</div><p>GitHub projects will appear here.</p></div></div></section>
  </main>
  <footer class="shell" id="contact">Learning → building → reflecting. <a href="mailto:preethamkp642@gmail.com">Say hello</a> · <a href="https://www.linkedin.com/in/preethamkp/">LinkedIn</a></footer>
  <script>
    const username = "Preetham-18";
    const api = `https://api.github.com/users/${username}`;
    const formatNumber = value => new Intl.NumberFormat("en-IN").format(value || 0);
    fetch(api).then(response => response.json()).then(profile => { document.querySelector("#repos").textContent = formatNumber(profile.public_repos); document.querySelector("#followers").textContent = formatNumber(profile.followers); document.querySelector("#following").textContent = formatNumber(profile.following); document.querySelector("#joined").textContent = new Date(profile.created_at).getFullYear(); }).catch(() => document.querySelector("#repo-note").textContent = "GITHUB PROFILE / PREETHAM-18");
    fetch(`${api}/repos?sort=updated&per_page=4`).then(response => response.json()).then(repositories => { const grid = document.querySelector("#repo-grid"); grid.innerHTML = repositories.map(repo => `<a class="repo" href="${repo.html_url}"><div class="repo-title"><span>↗</span>${repo.name}</div><p>${repo.description || "A project from my learning journey."}</p><div class="repo-meta"><span><i class="dot"></i>${repo.language || "Code"}</span><span>★ ${repo.stargazers_count}</span><span>⑂ ${repo.forks_count}</span></div></a>`).join(""); document.querySelector("#repo-note").textContent = "RECENTLY UPDATED / GITHUB API"; }).catch(() => document.querySelector("#repo-note").textContent = "VIEW ALL WORK ON GITHUB ↗");
  </script>
</body>
</html>
