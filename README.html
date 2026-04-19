<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KHURAM — AI Engineer</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Bebas+Neue&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --acid: #00ff41;
    --acid-dim: #00cc33;
    --bg: #080b08;
    --bg2: #0d110d;
    --bg3: #111811;
    --surface: #141a14;
    --surface2: #1a221a;
    --border: #1f2e1f;
    --text: #c8d8c8;
    --text-dim: #6b836b;
    --red: #ff4040;
    --blue: #4087ff;
    --gold: #ffd700;
    --purple: #c084fc;
    --mono: 'Space Mono', monospace;
    --display: 'Bebas Neue', cursive;
    --body: 'Inter', sans-serif;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--body);
    overflow-x: hidden;
    cursor: crosshair;
  }

  /* SCANLINE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background: repeating-linear-gradient(
      0deg,
      transparent,
      transparent 2px,
      rgba(0,255,65,0.015) 2px,
      rgba(0,255,65,0.015) 4px
    );
    pointer-events: none;
    z-index: 9999;
    animation: scanMove 8s linear infinite;
  }

  @keyframes scanMove {
    0% { background-position: 0 0; }
    100% { background-position: 0 100px; }
  }

  /* GRID BG */
  .grid-bg {
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,255,65,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,255,65,0.03) 1px, transparent 1px);
    background-size: 40px 40px;
    pointer-events: none;
    z-index: 0;
  }

  /* NOISE */
  .noise {
    position: fixed;
    inset: 0;
    opacity: 0.04;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
  }

  main { position: relative; z-index: 1; max-width: 900px; margin: 0 auto; padding: 0 20px; }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 80px 0 60px;
    position: relative;
  }

  .hero-eyebrow {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--acid);
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-bottom: 28px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .hero-eyebrow::before {
    content: '';
    width: 40px;
    height: 1px;
    background: var(--acid);
  }

  .blink {
    display: inline-block;
    width: 8px;
    height: 14px;
    background: var(--acid);
    animation: blink 1s step-end infinite;
    margin-left: 4px;
  }

  @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0; } }

  .hero-name {
    font-family: var(--display);
    font-size: clamp(64px, 14vw, 140px);
    line-height: 0.9;
    letter-spacing: 2px;
    color: #fff;
    margin-bottom: 8px;
    position: relative;
  }

  .hero-name .glitch {
    position: relative;
    display: inline-block;
  }

  .hero-name .glitch::before,
  .hero-name .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    overflow: hidden;
  }

  .hero-name .glitch::before {
    color: var(--red);
    animation: glitch1 4s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 35%, 0 35%);
  }

  .hero-name .glitch::after {
    color: var(--blue);
    animation: glitch2 4s infinite;
    clip-path: polygon(0 65%, 100% 65%, 100% 100%, 0 100%);
  }

  @keyframes glitch1 {
    0%,95%,100% { transform: translateX(0); opacity: 0; }
    96% { transform: translateX(-4px); opacity: 0.8; }
    97% { transform: translateX(4px); opacity: 0.8; }
    98% { transform: translateX(-2px); opacity: 0.8; }
  }

  @keyframes glitch2 {
    0%,95%,100% { transform: translateX(0); opacity: 0; }
    96% { transform: translateX(4px); opacity: 0.8; }
    97% { transform: translateX(-4px); opacity: 0.8; }
    98% { transform: translateX(2px); opacity: 0.8; }
  }

  .hero-sub {
    font-family: var(--mono);
    font-size: clamp(12px, 2vw, 16px);
    color: var(--acid);
    margin-bottom: 32px;
    letter-spacing: 1px;
  }

  .hero-desc {
    font-size: 15px;
    color: var(--text-dim);
    line-height: 1.7;
    max-width: 520px;
    margin-bottom: 48px;
  }

  .hero-desc strong { color: var(--text); font-weight: 500; }

  .hero-ctas {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
  }

  .btn {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
    padding: 14px 28px;
    border: 1px solid;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 8px;
    transition: all 0.2s;
    cursor: pointer;
    background: none;
  }

  .btn-primary {
    border-color: var(--acid);
    color: var(--acid);
    background: rgba(0,255,65,0.05);
  }

  .btn-primary:hover {
    background: var(--acid);
    color: var(--bg);
    box-shadow: 0 0 30px rgba(0,255,65,0.4);
  }

  .btn-ghost {
    border-color: var(--border);
    color: var(--text-dim);
  }

  .btn-ghost:hover {
    border-color: var(--text-dim);
    color: var(--text);
  }

  /* STATUS BAR */
  .status-bar {
    position: fixed;
    top: 0; left: 0; right: 0;
    height: 40px;
    background: rgba(8,11,8,0.95);
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    padding: 0 24px;
    gap: 24px;
    font-family: var(--mono);
    font-size: 10px;
    color: var(--text-dim);
    z-index: 1000;
    backdrop-filter: blur(10px);
    overflow: hidden;
  }

  .status-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--acid);
    box-shadow: 0 0 8px var(--acid);
    animation: pulse 2s ease-in-out infinite;
    flex-shrink: 0;
  }

  @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.3; } }

  .status-text { color: var(--acid); white-space: nowrap; }

  .status-ticker {
    margin-left: auto;
    overflow: hidden;
    max-width: 300px;
    white-space: nowrap;
  }

  .ticker-inner {
    display: inline-block;
    animation: ticker 20s linear infinite;
    color: var(--text-dim);
  }

  @keyframes ticker { 0% { transform: translateX(100%); } 100% { transform: translateX(-100%); } }

  /* SECTION */
  section { padding: 80px 0; border-top: 1px solid var(--border); }

  .section-label {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--acid);
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  .section-title {
    font-family: var(--display);
    font-size: clamp(36px, 7vw, 72px);
    color: #fff;
    line-height: 1;
    margin-bottom: 48px;
  }

  /* EXPERIENCE */
  .exp-list { display: flex; flex-direction: column; gap: 2px; }

  .exp-item {
    display: grid;
    grid-template-columns: 120px 1fr;
    gap: 0;
    position: relative;
    cursor: default;
  }

  @media (max-width: 600px) {
    .exp-item { grid-template-columns: 1fr; }
    .exp-date { margin-bottom: 8px; }
  }

  .exp-date {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--text-dim);
    padding: 24px 20px 24px 0;
    border-right: 1px solid var(--border);
    position: relative;
    line-height: 1.6;
  }

  .exp-date::after {
    content: '';
    position: absolute;
    right: -4px;
    top: 28px;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--border);
    transition: background 0.2s;
  }

  .exp-item:hover .exp-date::after { background: var(--acid); box-shadow: 0 0 10px var(--acid); }

  .exp-content {
    padding: 24px 0 24px 28px;
    transition: background 0.2s;
  }

  .exp-item:hover .exp-content { background: rgba(0,255,65,0.02); }

  .exp-company {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--acid);
    letter-spacing: 2px;
    margin-bottom: 4px;
  }

  .exp-role {
    font-size: 17px;
    font-weight: 600;
    color: #fff;
    margin-bottom: 12px;
  }

  .exp-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }

  .tag {
    font-family: var(--mono);
    font-size: 10px;
    padding: 3px 10px;
    border: 1px solid var(--border);
    color: var(--text-dim);
    letter-spacing: 0.5px;
  }

  .tag-green { border-color: rgba(0,255,65,0.3); color: var(--acid-dim); }
  .tag-blue { border-color: rgba(64,135,255,0.3); color: var(--blue); }
  .tag-purple { border-color: rgba(192,132,252,0.3); color: var(--purple); }
  .tag-gold { border-color: rgba(255,215,0,0.3); color: var(--gold); }

  /* PROJECTS */
  .projects-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2px;
  }

  @media (max-width: 640px) { .projects-grid { grid-template-columns: 1fr; } }

  .project-card {
    background: var(--surface);
    padding: 32px;
    border: 1px solid var(--border);
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
    cursor: default;
  }

  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 2px;
    background: var(--acid);
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s;
  }

  .project-card:hover { border-color: rgba(0,255,65,0.3); }
  .project-card:hover::before { transform: scaleX(1); }

  .project-num {
    font-family: var(--mono);
    font-size: 48px;
    color: var(--border);
    line-height: 1;
    margin-bottom: 16px;
    transition: color 0.3s;
  }

  .project-card:hover .project-num { color: rgba(0,255,65,0.15); }

  .project-name {
    font-size: 18px;
    font-weight: 600;
    color: #fff;
    margin-bottom: 10px;
  }

  .project-desc {
    font-size: 13px;
    color: var(--text-dim);
    line-height: 1.6;
    margin-bottom: 20px;
  }

  .project-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }

  /* SKILLS */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 2px;
  }

  .skill-group {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 24px;
  }

  .skill-group-label {
    font-family: var(--mono);
    font-size: 9px;
    color: var(--acid);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 16px;
    padding-bottom: 10px;
    border-bottom: 1px solid var(--border);
  }

  .skill-item {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text-dim);
    padding: 5px 0;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: color 0.2s;
  }

  .skill-item:hover { color: var(--text); }

  .skill-item::before {
    content: '›';
    color: var(--acid);
    opacity: 0.6;
  }

  /* COLLABORATE */
  .collab-section {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 60px 48px;
    position: relative;
    overflow: hidden;
  }

  @media (max-width: 600px) { .collab-section { padding: 40px 24px; } }

  .collab-section::after {
    content: 'COLLABORATE';
    position: absolute;
    right: -20px;
    top: 50%;
    transform: translateY(-50%) rotate(90deg);
    font-family: var(--display);
    font-size: 120px;
    color: rgba(0,255,65,0.03);
    white-space: nowrap;
    pointer-events: none;
  }

  .collab-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 48px;
    align-items: center;
  }

  @media (max-width: 640px) { .collab-grid { grid-template-columns: 1fr; gap: 32px; } }

  .collab-title {
    font-family: var(--display);
    font-size: clamp(40px, 8vw, 72px);
    color: #fff;
    line-height: 1;
    margin-bottom: 16px;
  }

  .collab-title span { color: var(--acid); }

  .collab-body {
    font-size: 14px;
    color: var(--text-dim);
    line-height: 1.8;
    margin-bottom: 32px;
  }

  .collab-interests {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }

  .collab-interest {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    font-size: 13px;
    color: var(--text-dim);
    line-height: 1.5;
  }

  .collab-interest-icon {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--acid);
    padding: 2px 8px;
    border: 1px solid rgba(0,255,65,0.3);
    white-space: nowrap;
    flex-shrink: 0;
    margin-top: 2px;
  }

  /* CONTACT */
  .contact-links {
    display: flex;
    flex-direction: column;
    gap: 2px;
    margin-top: 48px;
  }

  .contact-link {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 24px;
    border: 1px solid var(--border);
    text-decoration: none;
    transition: all 0.2s;
    background: var(--surface);
  }

  .contact-link:hover {
    border-color: rgba(0,255,65,0.4);
    background: rgba(0,255,65,0.04);
    transform: translateX(4px);
  }

  .contact-link-left {
    display: flex;
    align-items: center;
    gap: 16px;
  }

  .contact-link-icon {
    width: 36px;
    height: 36px;
    border: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
    flex-shrink: 0;
  }

  .contact-link-label {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--acid);
    letter-spacing: 2px;
    display: block;
    margin-bottom: 2px;
  }

  .contact-link-value {
    font-size: 13px;
    color: var(--text);
    word-break: break-all;
  }

  .contact-link-arrow {
    color: var(--text-dim);
    transition: transform 0.2s;
    font-size: 18px;
    flex-shrink: 0;
  }

  .contact-link:hover .contact-link-arrow { transform: translateX(6px); color: var(--acid); }

  /* FOOTER */
  footer {
    padding: 48px 0;
    border-top: 1px solid var(--border);
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: gap;
    gap: 16px;
  }

  footer .mono { font-family: var(--mono); font-size: 10px; color: var(--text-dim); }

  /* HERO DECORATION */
  .hero-decor {
    position: absolute;
    right: -60px;
    top: 50%;
    transform: translateY(-50%);
    font-family: var(--display);
    font-size: clamp(100px, 20vw, 200px);
    color: rgba(0,255,65,0.04);
    letter-spacing: -10px;
    pointer-events: none;
    white-space: nowrap;
    line-height: 1;
  }

  @media (max-width: 600px) { .hero-decor { display: none; } }

  /* TERMINAL BLOCK */
  .terminal {
    background: #0a0e0a;
    border: 1px solid var(--border);
    padding: 20px 24px;
    margin-bottom: 48px;
    font-family: var(--mono);
    font-size: 12px;
    line-height: 1.8;
    position: relative;
  }

  .terminal::before {
    content: '● ● ●';
    display: block;
    color: var(--text-dim);
    margin-bottom: 16px;
    letter-spacing: 4px;
    font-size: 8px;
  }

  .terminal .line { color: var(--text-dim); }
  .terminal .line .prompt { color: var(--acid); }
  .terminal .line .out { color: var(--text); }
  .terminal .line .comment { color: var(--text-dim); opacity: 0.5; }
  .terminal .line .val { color: var(--purple); }
  .terminal .line .key { color: var(--blue); }

  /* FADE IN */
  .fade-in {
    opacity: 0;
    transform: translateY(24px);
    animation: fadeUp 0.7s forwards;
  }

  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-in:nth-child(1) { animation-delay: 0.1s; }
  .fade-in:nth-child(2) { animation-delay: 0.2s; }
  .fade-in:nth-child(3) { animation-delay: 0.3s; }
  .fade-in:nth-child(4) { animation-delay: 0.4s; }
  .fade-in:nth-child(5) { animation-delay: 0.5s; }

  /* NAV */
  nav {
    position: fixed;
    right: 24px;
    top: 50%;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    gap: 14px;
    z-index: 100;
  }

  @media (max-width: 768px) { nav { display: none; } }

  .nav-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--border);
    cursor: pointer;
    transition: all 0.2s;
    position: relative;
  }

  .nav-dot:hover, .nav-dot.active {
    background: var(--acid);
    box-shadow: 0 0 10px var(--acid);
  }

  .nav-dot::after {
    content: attr(data-label);
    position: absolute;
    right: 16px;
    top: 50%;
    transform: translateY(-50%);
    font-family: var(--mono);
    font-size: 9px;
    color: var(--acid);
    letter-spacing: 2px;
    white-space: nowrap;
    opacity: 0;
    transition: opacity 0.2s;
  }

  .nav-dot:hover::after { opacity: 1; }
</style>
</head>
<body>

<div class="grid-bg"></div>
<div class="noise"></div>

<!-- STATUS BAR -->
<div class="status-bar">
  <div class="status-dot"></div>
  <span class="status-text">SYS:ONLINE</span>
  <span class="mono" style="display:none; sm:inline">GPA:3.36</span>
  <span class="mono" style="color:var(--text-dim)">COMSATS · ISB · PK</span>
  <div class="status-ticker">
    <span class="ticker-inner">◈ RAG SYSTEMS ◈ LLM FINE-TUNING ◈ AGENTIC AI ◈ LANGGRAPH ◈ DIFFUSION MODELS ◈ MULTIAGENT FRAMEWORKS ◈ FASTAPI ◈ DJANGO ◈ AWS ◈ OPEN TO COLLABORATE ◈</span>
  </div>
</div>

<!-- SIDE NAV -->
<nav>
  <div class="nav-dot active" data-label="INIT" onclick="scrollTo({top:0,behavior:'smooth'})"></div>
  <div class="nav-dot" data-label="EXP" onclick="document.getElementById('exp').scrollIntoView({behavior:'smooth'})"></div>
  <div class="nav-dot" data-label="BUILD" onclick="document.getElementById('projects').scrollIntoView({behavior:'smooth'})"></div>
  <div class="nav-dot" data-label="STACK" onclick="document.getElementById('skills').scrollIntoView({behavior:'smooth'})"></div>
  <div class="nav-dot" data-label="COLLAB" onclick="document.getElementById('collab').scrollIntoView({behavior:'smooth'})"></div>
  <div class="nav-dot" data-label="CONNECT" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})"></div>
</nav>

<main>
  <!-- HERO -->
  <section class="hero" id="hero">
    <div class="hero-decor">AI</div>

    <div class="fade-in">
      <p class="hero-eyebrow">AI Engineer<span class="blink"></span></p>
    </div>

    <div class="fade-in">
      <h1 class="hero-name">
        <span class="glitch" data-text="KHURAM">KHURAM</span>
      </h1>
      <h1 class="hero-name" style="color: var(--acid); font-size: clamp(40px,8vw,80px); margin-bottom: 24px;">SHAHZAD</h1>
    </div>

    <div class="fade-in">
      <p class="hero-sub">FastAPI · Django · Node.js · MySQL · MongoDB · RAG · AWS · Machine Learning · Deep Learning · ReactJS · VectorDB · Fine-Tuning · Data Annotation · Docker · Kubernetes · Grafana · Azure AI Foundry</p>
    </div>

    <div class="fade-in">
      <div class="terminal">
        <div class="line"><span class="prompt">$</span> <span class="out">whoami</span></div>
        <div class="line"><span class="key">name</span>: <span class="val">"Khuram Shahzad"</span></div>
        <div class="line"><span class="key">status</span>: <span style="color:var(--acid)">"actively_building"</span></div>
        <div class="line"><span class="key">focus</span>: <span class="val">"Agentic AI & Graph Compilers"</span></div>
        <div class="line"><span class="key">location</span>: <span class="val">"Islamabad, PK 🇵🇰"</span></div>
        <div class="line"><span class="key">open_to</span>: <span style="color:var(--gold)">"collaborations, projects, internships"</span> <span class="comment">// YES</span></div>
      </div>
    </div>

    <div class="fade-in">
      <div class="hero-ctas">
        <a href="mailto:khuramshahzad972001@gmail.com" class="btn btn-primary">⌗ Hire Me</a>
        <a href="https://github.com/khuramshahz" class="btn btn-ghost">↗ GitHub</a>
        <a href="#collab" onclick="document.getElementById('collab').scrollIntoView({behavior:'smooth'}); return false;" class="btn btn-ghost">⊕ Collaborate</a>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="exp">
    <p class="section-label">// WORK LOG</p>
    <h2 class="section-title">EXPERIENCE</h2>

    <div class="exp-list">
      <div class="exp-item">
        <div class="exp-date">
          MAR 2026<br>→ NOW
        </div>
        <div class="exp-content">
          <p class="exp-company">ROBX.AI</p>
          <p class="exp-role">Python Developer</p>
          <div class="exp-tags">
            <span class="tag tag-gold">Python Scripting</span>
            <span class="tag tag-gold">Automation</span>
            <span class="tag tag-gold">API Integration</span>
            <span class="tag tag-gold">Data Processing</span>
            <span class="tag tag-gold">FastAPI</span>
            <span class="tag tag-gold">Django</span>
            <span class="tag tag-gold">Node.js</span>
            <span class="tag tag-gold">Feature Engineering</span>
            <span class="tag tag-gold">AWS Deployment</span>
          </div>
        </div>
      </div>

      <div class="exp-item">
        <div class="exp-date">
          DEC 2025<br>→ FEB 28
        </div>
        <div class="exp-content">
          <p class="exp-company">ROBX.AI</p>
          <p class="exp-role">AI Intern</p>
          <div class="exp-tags">
            <span class="tag tag-green">RAG Chatbots</span>
            <span class="tag tag-green">LoRA / QLoRA Fine-tuning</span>
            <span class="tag tag-green">LangGraph Orchestration</span>
            <span class="tag tag-green">Multi-Agent Frameworks</span>
          </div>
        </div>
      </div>

      <div class="exp-item">
        <div class="exp-date">
          JUL 2025<br>→ SEP 2025
        </div>
        <div class="exp-content">
          <p class="exp-company">TRUST NEXUS</p>
          <p class="exp-role">AI Intern</p>
          <div class="exp-tags">
            <span class="tag tag-blue">FastAPI Microservices</span>
            <span class="tag tag-blue">Django REST</span>
            <span class="tag tag-blue">Computer Vision</span>
            <span class="tag tag-blue">Deep Learning Security</span>
          </div>
        </div>
      </div>

      <div class="exp-item">
        <div class="exp-date">
          JUL 2024<br>→ SEP 2024
        </div>
        <div class="exp-content">
          <p class="exp-company">KREASHION</p>
          <p class="exp-role">Laravel Intern — Full Stack</p>
          <div class="exp-tags">
            <span class="tag tag-purple">Laravel / PHP</span>
            <span class="tag tag-purple">RESTful APIs</span>
            <span class="tag tag-purple">MVC Architecture</span>
            <span class="tag tag-purple">Database Optimization</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <p class="section-label">// BUILD LOG</p>
    <h2 class="section-title">DEPLOYED</h2>

    <div class="projects-grid">
      <div class="project-card">
        <div class="project-num">01</div>
        <p class="project-name">Agentic Graph Compiler</p>
        <p class="project-desc">State-machine powered multi-agent system with dynamic graph-based workflows, parallel execution, and real-time decision routing.</p>
        <div class="project-stack">
          <span class="tag tag-green">LangGraph</span>
          <span class="tag tag-green">Python</span>
          <span class="tag tag-green">Redis</span>
          <span class="tag tag-green">NetworkX</span>
        </div>
      </div>

      <div class="project-card">
        <div class="project-num">02</div>
        <p class="project-name">Criminal Law Chatbot</p>
        <p class="project-desc">RAG-powered Pakistani legal AI with case law citation, multi-turn memory, and real-time legal reasoning over a curated vector knowledge base.</p>
        <div class="project-stack">
          <span class="tag tag-blue">FastAPI</span>
          <span class="tag tag-blue">React</span>
          <span class="tag tag-blue">MongoDB</span>
          <span class="tag tag-blue">LangChain</span>
        </div>
      </div>

      <div class="project-card">
        <div class="project-num">03</div>
        <p class="project-name">Celebrity Oracle</p>
        <p class="project-desc">Deep CNN with ResNet50 transfer learning achieving 94.2% validation accuracy over a 10,000+ celebrity recognition database with real-time inference.</p>
        <div class="project-stack">
          <span class="tag tag-purple">TensorFlow</span>
          <span class="tag tag-purple">Keras</span>
          <span class="tag tag-purple">OpenCV</span>
          <span class="tag tag-purple">ResNet50</span>
        </div>
      </div>

      <div class="project-card">
        <div class="project-num">04</div>
        <p class="project-name">Ollama Slide Architect</p>
        <p class="project-desc">AI-powered presentation generator using local LLMs to auto-create structured slides with professional templates and PPTX export.</p>
        <div class="project-stack">
          <span class="tag tag-gold">Ollama</span>
          <span class="tag tag-gold">Node.js</span>
          <span class="tag tag-gold">PptxGenJS</span>
          <span class="tag tag-gold">Express</span>
        </div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <p class="section-label">// TECH ARSENAL</p>
    <h2 class="section-title">STACK</h2>

    <div class="skills-grid">
      <div class="skill-group">
        <p class="skill-group-label">Generative AI</p>
        <div class="skill-item">LangChain / LangGraph</div>
        <div class="skill-item">RAG Pipelines</div>
        <div class="skill-item">LoRA / QLoRA</div>
        <div class="skill-item">Diffusion Models</div>
        <div class="skill-item">GANs</div>
        <div class="skill-item">Hugging Face</div>
        <div class="skill-item">OpenAI APIs</div>
      </div>

      <div class="skill-group">
        <p class="skill-group-label">Deep Learning</p>
        <div class="skill-item">PyTorch</div>
        <div class="skill-item">TensorFlow / Keras</div>
        <div class="skill-item">CNNs / RNNs / LSTMs</div>
        <div class="skill-item">Transformers</div>
        <div class="skill-item">Transfer Learning</div>
        <div class="skill-item">Computer Vision</div>
      </div>

      <div class="skill-group">
        <p class="skill-group-label">Backend & APIs</p>
        <div class="skill-item">FastAPI</div>
        <div class="skill-item">Django REST</div>
        <div class="skill-item">Flask</div>
        <div class="skill-item">Node.js</div>
        <div class="skill-item">Laravel</div>
        <div class="skill-item">PostgreSQL / MongoDB</div>
      </div>

      <div class="skill-group">
        <p class="skill-group-label">MLOps & Infra</p>
        <div class="skill-item">Docker / Kubernetes</div>
        <div class="skill-item">AWS EC2</div>
        <div class="skill-item">CI/CD Pipelines</div>
        <div class="skill-item">Git / GitHub</div>
        <div class="skill-item">N8N Automation</div>
      </div>

      <div class="skill-group">
        <p class="skill-group-label">Databases</p>
        <div class="skill-item">MongoDB</div>
        <div class="skill-item">PostgreSQL</div>
        <div class="skill-item">Supabase</div>
        <div class="skill-item">Firebase</div>
        <div class="skill-item">Vector DBs</div>
        <div class="skill-item">MySQL</div>
      </div>
    </div>
  </section>

  <!-- COLLABORATE -->
  <section id="collab">
    <p class="section-label">// OPEN CHANNEL</p>
    <h2 class="section-title">LET'S BUILD</h2>

    <div class="collab-section">
      <div class="collab-grid">
        <div>
          <h3 class="collab-title">OPEN TO<br><span>COLLABORATE</span></h3>
          <p class="collab-body">
            I'm actively looking for projects, collaborations, and open-source contributions where AI meets real-world problems. If you're building something ambitious — let's talk.
          </p>
          <div class="hero-ctas">
            <a href="mailto:khuramshahzad972001@gmail.com" class="btn btn-primary">⌗ Reach Out</a>
          </div>
        </div>

        <div class="collab-interests">
          <p style="font-family:var(--mono);font-size:10px;color:var(--acid);letter-spacing:3px;margin-bottom:16px;">INTERESTED IN</p>

          <div class="collab-interest">
            <span class="collab-interest-icon">01</span>
            <span>Agentic AI systems with real autonomous decision-making loops and persistent state</span>
          </div>

          <div class="collab-interest">
            <span class="collab-interest-icon">02</span>
            <span>RAG applications solving domain-specific problems (legal, medical, finance)</span>
          </div>

          <div class="collab-interest">
            <span class="collab-interest-icon">03</span>
            <span>LLM fine-tuning on niche datasets using LoRA / QLoRA pipelines</span>
          </div>

          <div class="collab-interest">
            <span class="collab-interest-icon">04</span>
            <span>Open source AI tools, developer productivity, and model deployment infrastructure</span>
          </div>

          <div class="collab-interest">
            <span class="collab-interest-icon">05</span>
            <span>Research into graph-based compilers and multi-agent coordination</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <p class="section-label">// ESTABLISH CONNECTION</p>
    <h2 class="section-title">CONNECT</h2>

    <div class="contact-links">
      <a href="mailto:khuramshahzad972001@gmail.com" class="contact-link">
        <div class="contact-link-left">
          <div class="contact-link-icon">✉</div>
          <div>
            <span class="contact-link-label">EMAIL</span>
            <span class="contact-link-value">khuramshahzad972001@gmail.com</span>
          </div>
        </div>
        <span class="contact-link-arrow">→</span>
      </a>

      <a href="https://github.com/khuramshahz" target="_blank" class="contact-link">
        <div class="contact-link-left">
          <div class="contact-link-icon">⌥</div>
          <div>
            <span class="contact-link-label">GITHUB</span>
            <span class="contact-link-value">github.com/khuramshahz</span>
          </div>
        </div>
        <span class="contact-link-arrow">→</span>
      </a>

      <a href="https://www.linkedin.com/in/khuram-shahzad-87a0472b5" target="_blank" class="contact-link">
        <div class="contact-link-left">
          <div class="contact-link-icon">◈</div>
          <div>
            <span class="contact-link-label">LINKEDIN</span>
            <span class="contact-link-value">linkedin.com/in/khuram-shahzad-87a0472b5</span>
          </div>
        </div>
        <span class="contact-link-arrow">→</span>
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p class="mono">KHURAM SHAHZAD · COMSATS ISB · SP26</p>
    <p class="mono" style="color:var(--acid)">READY_TO_DEPLOY</p>
  </footer>
</main>

<script>
  // Nav dot active state
  const sections = document.querySelectorAll('section[id], main > section');
  const dots = document.querySelectorAll('.nav-dot');
  const ids = ['hero','exp','projects','skills','collab','contact'];

  window.addEventListener('scroll', () => {
    let current = 0;
    ids.forEach((id, i) => {
      const el = document.getElementById(id);
      if (el && window.scrollY >= el.offsetTop - 200) current = i;
    });
    dots.forEach((d, i) => d.classList.toggle('active', i === current));
  });

  // Intersection observer for fade-ins
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.style.opacity = '1';
        e.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.project-card, .skill-group, .exp-item, .contact-link').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    el.style.transition = 'opacity 0.5s ease, transform 0.5s ease, border-color 0.3s, background 0.2s';
    observer.observe(el);
  });
</script>
</body>
</html>
