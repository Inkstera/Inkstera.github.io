<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Quoterie — ศิลปะแห่งคำพูด</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400;1,700&family=Noto+Serif+Thai:wght@300;400;600&family=DM+Mono:ital@0;1&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --ink: #1a1209;
      --cream: #f5f0e8;
      --parchment: #ede6d3;
      --gold: #c9a84c;
      --gold-light: #e8c97a;
      --rust: #a0522d;
      --warm-gray: #8b7d6b;
      --paper: #faf7f2;
    }

    html { scroll-behavior: smooth; }

    body {
      background-color: var(--paper);
      color: var(--ink);
      font-family: 'Noto Serif Thai', 'Playfair Display', serif;
      overflow-x: hidden;
      cursor: default;
    }

    /* ── NOISE TEXTURE OVERLAY ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 999;
      opacity: 0.6;
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1.5rem 4rem;
      background: rgba(245, 240, 232, 0.85);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(201, 168, 76, 0.2);
    }

    .nav-logo {
      font-family: 'Playfair Display', serif;
      font-size: 1.6rem;
      font-weight: 700;
      letter-spacing: -0.02em;
      color: var(--ink);
      text-decoration: none;
    }
    .nav-logo span { color: var(--gold); font-style: italic; }

    .nav-links {
      display: flex;
      gap: 2.5rem;
      list-style: none;
    }
    .nav-links a {
      font-family: 'DM Mono', monospace;
      font-size: 0.75rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--warm-gray);
      text-decoration: none;
      transition: color 0.3s;
    }
    .nav-links a:hover { color: var(--gold); }

    .nav-cta {
      font-family: 'DM Mono', monospace;
      font-size: 0.75rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      padding: 0.6rem 1.4rem;
      border: 1.5px solid var(--gold);
      color: var(--gold);
      text-decoration: none;
      transition: all 0.3s;
    }
    .nav-cta:hover {
      background: var(--gold);
      color: var(--ink);
    }

    /* ── HERO ── */
    .hero {
      min-height: 100vh;
      display: grid;
      grid-template-columns: 1fr 1fr;
      position: relative;
      overflow: hidden;
    }

    .hero-left {
      padding: 12rem 4rem 6rem 7rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      position: relative;
      z-index: 2;
    }

    .hero-tag {
      font-family: 'DM Mono', monospace;
      font-size: 0.7rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 2rem;
      display: flex;
      align-items: center;
      gap: 0.8rem;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.2s forwards;
    }
    .hero-tag::before {
      content: '';
      width: 2.5rem;
      height: 1px;
      background: var(--gold);
    }

    .hero-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(3.2rem, 5vw, 5.5rem);
      font-weight: 700;
      line-height: 1.1;
      letter-spacing: -0.03em;
      margin-bottom: 1.5rem;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.4s forwards;
    }
    .hero-title em {
      font-style: italic;
      color: var(--gold);
    }

    .hero-sub {
      font-size: 1.05rem;
      font-weight: 300;
      line-height: 1.8;
      color: var(--warm-gray);
      max-width: 38ch;
      margin-bottom: 3rem;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.6s forwards;
    }

    .hero-actions {
      display: flex;
      gap: 1.2rem;
      align-items: center;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.8s forwards;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: 0.6rem;
      padding: 1rem 2.2rem;
      background: var(--ink);
      color: var(--cream);
      text-decoration: none;
      font-family: 'DM Mono', monospace;
      font-size: 0.78rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
    }
    .btn-primary::after {
      content: '';
      position: absolute;
      inset: 0;
      background: var(--gold);
      transform: translateX(-101%);
      transition: transform 0.35s ease;
    }
    .btn-primary:hover::after { transform: translateX(0); }
    .btn-primary span { position: relative; z-index: 1; }

    .btn-ghost {
      font-family: 'DM Mono', monospace;
      font-size: 0.75rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--warm-gray);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 0.5rem;
      transition: color 0.3s;
    }
    .btn-ghost:hover { color: var(--ink); }
    .btn-ghost .arrow { transition: transform 0.3s; }
    .btn-ghost:hover .arrow { transform: translateX(4px); }

    /* ── HERO RIGHT ── */
    .hero-right {
      position: relative;
      background: var(--parchment);
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }

    .hero-right::before {
      content: '"';
      position: absolute;
      font-family: 'Playfair Display', serif;
      font-size: 40vw;
      font-weight: 700;
      color: rgba(201, 168, 76, 0.07);
      top: -10%;
      left: -5%;
      line-height: 1;
      pointer-events: none;
    }

    .quote-card {
      position: relative;
      width: 360px;
      padding: 3rem 3.5rem;
      background: var(--paper);
      border-left: 3px solid var(--gold);
      box-shadow: 20px 20px 0 var(--parchment), 22px 22px 0 rgba(201,168,76,0.3);
      opacity: 0;
      transform: translateY(20px) rotate(1.5deg);
      animation: cardReveal 1s ease 1s forwards;
    }

    @keyframes cardReveal {
      to { opacity: 1; transform: translateY(0) rotate(1.5deg); }
    }

    .quote-card-mark {
      font-family: 'Playfair Display', serif;
      font-size: 5rem;
      line-height: 0.7;
      color: var(--gold);
      margin-bottom: 1rem;
      display: block;
    }

    .quote-card-text {
      font-family: 'Playfair Display', serif;
      font-size: 1.15rem;
      font-style: italic;
      line-height: 1.75;
      color: var(--ink);
      margin-bottom: 1.5rem;
    }

    .quote-card-author {
      font-family: 'DM Mono', monospace;
      font-size: 0.7rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--warm-gray);
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }
    .quote-card-author::before {
      content: '';
      width: 1.5rem;
      height: 1px;
      background: var(--warm-gray);
    }

    /* ── SCROLL HINT ── */
    .scroll-hint {
      position: absolute;
      bottom: 2.5rem;
      left: 7rem;
      display: flex;
      align-items: center;
      gap: 0.8rem;
      font-family: 'DM Mono', monospace;
      font-size: 0.65rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: var(--warm-gray);
      opacity: 0;
      animation: fadeUp 0.8s ease 1.4s forwards;
    }
    .scroll-line {
      width: 1px;
      height: 3rem;
      background: linear-gradient(to bottom, var(--gold), transparent);
      animation: scrollPulse 2s ease-in-out 1.6s infinite;
    }

    @keyframes scrollPulse {
      0%, 100% { opacity: 1; transform: scaleY(1); transform-origin: top; }
      50% { opacity: 0.4; transform: scaleY(0.6); transform-origin: top; }
    }

    /* ── STATS BAND ── */
    .stats-band {
      background: var(--ink);
      color: var(--cream);
      padding: 3rem 7rem;
      display: flex;
      gap: 0;
      overflow: hidden;
    }

    .stat-item {
      flex: 1;
      padding: 0 3rem;
      border-right: 1px solid rgba(245, 240, 232, 0.1);
      opacity: 0;
      animation: fadeUp 0.6s ease calc(0.1s * var(--i)) forwards;
    }
    .stat-item:first-child { padding-left: 0; }
    .stat-item:last-child { border-right: none; }

    .stat-num {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      font-weight: 700;
      letter-spacing: -0.04em;
      color: var(--gold-light);
      display: block;
    }
    .stat-label {
      font-family: 'DM Mono', monospace;
      font-size: 0.65rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: rgba(245,240,232,0.5);
      margin-top: 0.4rem;
    }

    /* ── FEATURES ── */
    .features {
      padding: 9rem 7rem;
      position: relative;
    }

    .section-label {
      font-family: 'DM Mono', monospace;
      font-size: 0.7rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--gold);
      display: flex;
      align-items: center;
      gap: 0.8rem;
      margin-bottom: 1.2rem;
    }
    .section-label::before {
      content: '';
      width: 2rem;
      height: 1px;
      background: var(--gold);
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2rem, 3.5vw, 3.2rem);
      font-weight: 700;
      line-height: 1.2;
      letter-spacing: -0.02em;
      max-width: 20ch;
      margin-bottom: 5rem;
    }
    .section-title em { font-style: italic; color: var(--gold); }

    .features-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 3rem;
    }

    .feature-card {
      padding: 2.5rem;
      border: 1px solid rgba(139, 125, 107, 0.15);
      background: var(--cream);
      position: relative;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .feature-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 24px 40px rgba(26, 18, 9, 0.08);
    }

    .feature-num {
      font-family: 'Playfair Display', serif;
      font-size: 4rem;
      font-weight: 700;
      color: rgba(201, 168, 76, 0.15);
      line-height: 1;
      position: absolute;
      top: 1.5rem;
      right: 2rem;
    }

    .feature-icon {
      font-size: 1.8rem;
      margin-bottom: 1.5rem;
    }

    .feature-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.2rem;
      font-weight: 700;
      margin-bottom: 0.8rem;
    }

    .feature-desc {
      font-size: 0.9rem;
      line-height: 1.8;
      color: var(--warm-gray);
      font-weight: 300;
    }

    /* ── MARQUEE ── */
    .marquee-wrap {
      background: var(--parchment);
      padding: 2rem 0;
      overflow: hidden;
      border-top: 1px solid rgba(201,168,76,0.2);
      border-bottom: 1px solid rgba(201,168,76,0.2);
    }
    .marquee-track {
      display: flex;
      gap: 4rem;
      white-space: nowrap;
      animation: marquee 28s linear infinite;
    }
    .marquee-item {
      font-family: 'Playfair Display', serif;
      font-size: 1rem;
      font-style: italic;
      color: var(--warm-gray);
      flex-shrink: 0;
      display: flex;
      align-items: center;
      gap: 1.5rem;
    }
    .marquee-dot {
      width: 5px;
      height: 5px;
      background: var(--gold);
      border-radius: 50%;
      flex-shrink: 0;
    }

    @keyframes marquee {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    /* ── CTA SECTION ── */
    .cta-section {
      padding: 9rem 7rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 6rem;
      align-items: center;
    }

    .cta-left { position: relative; }

    .big-quote {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.4rem, 2.5vw, 2.2rem);
      font-style: italic;
      line-height: 1.6;
      color: var(--ink);
    }
    .big-quote-author {
      font-family: 'DM Mono', monospace;
      font-size: 0.72rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--warm-gray);
      margin-top: 2rem;
      display: flex;
      align-items: center;
      gap: 1rem;
    }
    .big-quote-author::before {
      content: '';
      width: 2rem;
      height: 1px;
      background: var(--gold);
    }

    .deco-border {
      position: absolute;
      top: -2rem;
      left: -2rem;
      right: 2rem;
      bottom: -2rem;
      border: 1px solid rgba(201,168,76,0.25);
      pointer-events: none;
    }

    .cta-right {
      padding: 4rem;
      background: var(--ink);
      color: var(--cream);
    }

    .cta-right h3 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      font-weight: 700;
      line-height: 1.25;
      margin-bottom: 1rem;
    }
    .cta-right h3 em { font-style: italic; color: var(--gold-light); }

    .cta-right p {
      font-size: 0.9rem;
      line-height: 1.8;
      color: rgba(245,240,232,0.6);
      font-weight: 300;
      margin-bottom: 2.5rem;
    }

    .cta-input-row {
      display: flex;
      gap: 0;
    }
    .cta-input {
      flex: 1;
      padding: 0.9rem 1.2rem;
      background: rgba(245,240,232,0.08);
      border: 1px solid rgba(245,240,232,0.15);
      border-right: none;
      color: var(--cream);
      font-family: 'DM Mono', monospace;
      font-size: 0.8rem;
      outline: none;
      transition: border-color 0.3s;
    }
    .cta-input::placeholder { color: rgba(245,240,232,0.3); }
    .cta-input:focus { border-color: var(--gold); }
    .cta-submit {
      padding: 0.9rem 1.5rem;
      background: var(--gold);
      border: none;
      color: var(--ink);
      font-family: 'DM Mono', monospace;
      font-size: 0.75rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      cursor: pointer;
      transition: background 0.3s;
    }
    .cta-submit:hover { background: var(--gold-light); }

    /* ── FOOTER ── */
    footer {
      background: var(--ink);
      color: rgba(245,240,232,0.5);
      padding: 3rem 7rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-top: 1px solid rgba(245,240,232,0.05);
    }

    .footer-logo {
      font-family: 'Playfair Display', serif;
      font-size: 1.2rem;
      font-weight: 700;
      color: var(--cream);
    }
    .footer-logo span { color: var(--gold); font-style: italic; }

    .footer-copy {
      font-family: 'DM Mono', monospace;
      font-size: 0.65rem;
      letter-spacing: 0.1em;
    }

    .footer-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }
    .footer-links a {
      font-family: 'DM Mono', monospace;
      font-size: 0.65rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: rgba(245,240,232,0.4);
      text-decoration: none;
      transition: color 0.3s;
    }
    .footer-links a:hover { color: var(--gold); }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 1024px) {
      nav { padding: 1.2rem 2rem; }
      .nav-links { display: none; }
      .hero { grid-template-columns: 1fr; min-height: auto; }
      .hero-left { padding: 9rem 2.5rem 4rem; }
      .hero-right { min-height: 400px; }
      .stats-band { padding: 3rem 2.5rem; flex-wrap: wrap; gap: 2rem; }
      .features { padding: 6rem 2.5rem; }
      .features-grid { grid-template-columns: 1fr; gap: 1.5rem; }
      .cta-section { grid-template-columns: 1fr; padding: 6rem 2.5rem; gap: 4rem; }
      footer { padding: 2rem 2.5rem; flex-direction: column; gap: 1.5rem; text-align: center; }
      .footer-links { justify-content: center; }
      .scroll-hint { left: 2.5rem; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a href="#" class="nav-logo">Quot<span>erie</span></a>
    <ul class="nav-links">
      <li><a href="#">สำรวจ</a></li>
      <li><a href="#">หมวดหมู่</a></li>
      <li><a href="#">นักเขียน</a></li>
      <li><a href="#">คอมมูนิตี้</a></li>
    </ul>
    <a href="#" class="nav-cta">เริ่มต้นฟรี</a>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-left">
      <div class="hero-tag">ศิลปะแห่งคำพูด</div>
      <h1 class="hero-title">
        ทุกคำพูด<br/>
        คือ<em>บทกวี</em><br/>
        ที่รอถูกเขียน
      </h1>
      <p class="hero-sub">
        แพลตฟอร์มสำหรับนักเขียนโควทที่ต้องการพื้นที่สร้างสรรค์ 
        บันทึก แบ่งปัน และค้นหาแรงบันดาลใจจากคำพูดที่ทรงพลัง
      </p>
      <div class="hero-actions">
        <a href="#" class="btn-primary">
          <span>เริ่มเขียนโควท</span>
          <span>→</span>
        </a>
        <a href="#" class="btn-ghost">
          ดูตัวอย่าง <span class="arrow">→</span>
        </a>
      </div>
    </div>

    <div class="hero-right">
      <div class="quote-card">
        <span class="quote-card-mark">"</span>
        <p class="quote-card-text">
          คำพูดที่ดีหนึ่งประโยค<br/>
          สามารถเปลี่ยนมุมมอง<br/>
          ของคนทั้งโลกได้
        </p>
        <div class="quote-card-author">Quoterie Team</div>
      </div>
    </div>

    <div class="scroll-hint">
      <div class="scroll-line"></div>
      เลื่อนลง
    </div>
  </section>

  <!-- STATS BAND -->
  <section class="stats-band">
    <div class="stat-item" style="--i:1">
      <span class="stat-num">12,000+</span>
      <div class="stat-label">โควทที่ถูกเขียน</div>
    </div>
    <div class="stat-item" style="--i:2">
      <span class="stat-num">3,400+</span>
      <div class="stat-label">นักเขียนในชุมชน</div>
    </div>
    <div class="stat-item" style="--i:3">
      <span class="stat-num">80+</span>
      <div class="stat-label">หมวดหมู่ความรู้สึก</div>
    </div>
    <div class="stat-item" style="--i:4">
      <span class="stat-num">∞</span>
      <div class="stat-label">แรงบันดาลใจ</div>
    </div>
  </section>

  <!-- MARQUEE -->
  <div class="marquee-wrap">
    <div class="marquee-track">
      <div class="marquee-item"><span class="marquee-dot"></span> ความรัก</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความหวัง</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความเจ็บปวด</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความฝัน</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ชีวิต</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ปรัชญา</div>
      <div class="marquee-item"><span class="marquee-dot"></span> แรงบันดาลใจ</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความสุข</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ธรรมชาติ</div>
      <div class="marquee-item"><span class="marquee-dot"></span> เวลา</div>
      <!-- duplicate for infinite loop -->
      <div class="marquee-item"><span class="marquee-dot"></span> ความรัก</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความหวัง</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความเจ็บปวด</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความฝัน</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ชีวิต</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ปรัชญา</div>
      <div class="marquee-item"><span class="marquee-dot"></span> แรงบันดาลใจ</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ความสุข</div>
      <div class="marquee-item"><span class="marquee-dot"></span> ธรรมชาติ</div>
      <div class="marquee-item"><span class="marquee-dot"></span> เวลา</div>
    </div>
  </div>

  <!-- FEATURES -->
  <section class="features">
    <div class="section-label">ฟีเจอร์หลัก</div>
    <h2 class="section-title">ทุกสิ่งที่คุณต้องการ<em>สร้างสรรค์</em></h2>

    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-num">01</div>
        <div class="feature-icon">✍️</div>
        <h3 class="feature-title">เขียนและจัดเก็บ</h3>
        <p class="feature-desc">
          บันทึกโควทของคุณในรูปแบบที่สวยงาม พร้อมแท็กหมวดหมู่ 
          อารมณ์ และวันที่ เพื่อค้นหาได้ง่ายในภายหลัง
        </p>
      </div>
      <div class="feature-card">
        <div class="feature-num">02</div>
        <div class="feature-icon">🎨</div>
        <h3 class="feature-title">ออกแบบภาพโควท</h3>
        <p class="feature-desc">
          เปลี่ยนโควทเป็นภาพสวยงามด้วยเครื่องมือดีไซน์ในตัว 
          พร้อมธีมสไตล์ต่างๆ สำหรับแชร์บน Social Media
        </p>
      </div>
      <div class="feature-card">
        <div class="feature-num">03</div>
        <div class="feature-icon">🌐</div>
        <h3 class="feature-title">ชุมชนนักเขียน</h3>
        <p class="feature-desc">
          เชื่อมต่อกับนักเขียนและผู้อ่านที่มีใจรัก ค้นพบโควทจากคนทั่วโลก 
          และรับแรงบันดาลใจใหม่ๆ ทุกวัน
        </p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta-section">
    <div class="cta-left">
      <div class="deco-border"></div>
      <div class="big-quote">
        "คำพูดคือสิ่งเล็กน้อย<br/>
        ที่สามารถสร้าง<br/>
        ความเปลี่ยนแปลงอันยิ่งใหญ่"
      </div>
      <div class="big-quote-author">Victor Hugo</div>
    </div>

    <div class="cta-right">
      <h3>เริ่มต้น<em>บทกวี</em><br/>ของคุณวันนี้</h3>
      <p>
        ลงทะเบียนฟรีและเริ่มบันทึกโควทแรกของคุณ 
        ไม่ต้องใช้บัตรเครดิต ไม่มีข้อผูกมัด
      </p>
      <div class="cta-input-row">
        <input class="cta-input" type="email" placeholder="อีเมลของคุณ" />
        <button class="cta-submit">เริ่มเลย</button>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-logo">Quot<span>erie</span></div>
    <p class="footer-copy">© 2026 Quoterie — ศิลปะแห่งคำพูด</p>
    <ul class="footer-links">
      <li><a href="#">เกี่ยวกับ</a></li>
      <li><a href="#">ความเป็นส่วนตัว</a></li>
      <li><a href="#">ติดต่อ</a></li>
    </ul>
  </footer>

</body>
</html>
