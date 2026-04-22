<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- ── SEO ── -->

<title>New Wave Nutrition | Protein Shakes & Loaded Teas | Palm Harbor, FL</title>
<meta name="description" content="New Wave Nutrition is Palm Harbor's favorite nutrition club. Fresh protein shakes, loaded teas, energy boosters, and Cardio Drumming classes. Mon–Fri 7–4, Sat–Sun 9–12. Call (727) 754-5124.">
<meta name="keywords" content="New Wave Nutrition, protein shakes Palm Harbor, loaded teas Palm Harbor, Herbalife Palm Harbor, nutrition club Florida, cardio drumming, healthy shakes Tarpon Springs">
<meta name="author" content="New Wave Nutrition">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://newwavenutrition.com/">

<!-- ── Open Graph (Facebook / social sharing) ── -->

<meta property="og:type" content="website">
<meta property="og:url" content="https://newwavenutrition.com/">
<meta property="og:title" content="New Wave Nutrition | Protein Shakes & Loaded Teas | Palm Harbor, FL">
<meta property="og:description" content="Handcrafted protein shakes, loaded teas & energy boosters made fresh daily. Palm Harbor, FL. Mon–Fri 7–4, Sat–Sun 9–12.">
<meta property="og:image" content="https://newwavenutrition.com/og-image.jpg">

<!-- ── Twitter Card ── -->

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="New Wave Nutrition | Protein Shakes & Loaded Teas">
<meta name="twitter:description" content="Fresh protein shakes, loaded teas & energy boosters. Palm Harbor, FL.">

<!-- ── Favicon placeholder (replace with your actual favicon) ── -->

<link rel="icon" type="image/png" href="favicon.png">
<link rel="apple-touch-icon" href="favicon.png">

<!-- ── Fonts ── -->

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,400;0,600;0,700;0,800;1,400&family=Pacifico&display=swap" rel="stylesheet">

<!-- ── Local Business structured data (Google) ── -->

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FoodEstablishment",
  "name": "New Wave Nutrition",
  "description": "Nutrition club serving handcrafted protein shakes, loaded teas, and energy boosters in Palm Harbor, FL. Also offering Cardio Drumming fitness classes.",
  "url": "https://newwavenutrition.com",
  "telephone": "+17277545124",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "1330 Tampa Rd",
    "addressLocality": "Palm Harbor",
    "addressRegion": "FL",
    "postalCode": "34683",
    "addressCountry": "US"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 28.0836,
    "longitude": -82.7654
  },
  "openingHoursSpecification": [
    { "@type": "OpeningHoursSpecification", "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"], "opens": "07:00", "closes": "16:00" },
    { "@type": "OpeningHoursSpecification", "dayOfWeek": ["Saturday","Sunday"], "opens": "09:00", "closes": "12:00" }
  ],
  "sameAs": [
    "https://www.facebook.com/newwavetampabay/",
    "https://www.instagram.com/new.wave.nutrition/",
    "https://www.tiktok.com/@newwavenutrition"
  ],
  "servesCuisine": "Health Food",
  "priceRange": "$"
}
</script>

<style>
  :root {
    --aqua:    #0BBFB2;
    --aqua-lt: #E0FAF8;
    --aqua-mid:#B2F0EC;
    --coral:   #FF6B6B;
    --coral-lt:#FFF0F0;
    --peach:   #FFA06A;
    --lemon:   #FFE066;
    --lemon-lt:#FFFBE0;
    --mint:    #D4F5EF;
    --cream:   #FFFDF8;
    --white:   #FFFFFF;
    --navy:    #1A3A35;
    --text:    #1E3A35;
    --muted:   #6B8F8A;
    --line:    rgba(11,191,178,0.18);
    --shadow:  0 4px 24px rgba(11,191,178,0.12);
  }

  *, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior:smooth; }
  body { font-family:'Nunito',sans-serif; background:var(--cream); color:var(--text); overflow-x:hidden; }

  /* ── NAV ── */
  nav {
    position:fixed; top:0; left:0; right:0; z-index:100;
    display:flex; align-items:center; justify-content:space-between;
    padding:1rem 3rem;
    background:rgba(255,253,248,0.95);
    backdrop-filter:blur(16px);
    -webkit-backdrop-filter:blur(16px);
    border-bottom:1px solid var(--line);
    box-shadow:0 2px 16px rgba(11,191,178,0.07);
  }
  .nav-logo { font-family:'Pacifico',cursive; font-size:1.4rem; color:var(--aqua); text-decoration:none; display:block; }
  .nav-logo span { color:var(--coral); }
  .nav-links { display:flex; gap:1.8rem; list-style:none; align-items:center; }
  .nav-links a { font-size:0.75rem; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:var(--muted); text-decoration:none; transition:color 0.2s; }
  .nav-links a:hover { color:var(--aqua); }
  .nav-cta { background:var(--coral) !important; color:white !important; padding:0.5rem 1.3rem; border-radius:100px; font-size:0.73rem !important; font-weight:800 !important; box-shadow:0 4px 14px rgba(255,107,107,0.3); transition:background 0.2s, transform 0.2s !important; }
  .nav-cta:hover { background:var(--peach) !important; transform:translateY(-1px); }

  /* ── MOBILE MENU ── */
  .hamburger { display:none; flex-direction:column; gap:5px; cursor:pointer; padding:4px; background:none; border:none; }
  .hamburger span { display:block; width:24px; height:2px; background:var(--navy); border-radius:2px; transition:all 0.3s; }
  .hamburger.open span:nth-child(1) { transform:rotate(45deg) translate(5px,5px); }
  .hamburger.open span:nth-child(2) { opacity:0; }
  .hamburger.open span:nth-child(3) { transform:rotate(-45deg) translate(5px,-5px); }
  .mobile-nav { display:none; position:fixed; top:62px; left:0; right:0; background:rgba(255,253,248,0.98); backdrop-filter:blur(16px); padding:1.5rem 2rem; border-bottom:1px solid var(--line); z-index:99; flex-direction:column; gap:1rem; }
  .mobile-nav.open { display:flex; }
  .mobile-nav a { font-size:0.85rem; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:var(--muted); text-decoration:none; padding:0.5rem 0; border-bottom:1px solid var(--line); }
  .mobile-nav a:last-child { border-bottom:none; background:var(--coral); color:white; text-align:center; padding:0.8rem; border-radius:100px; }

  /* ── HERO ── */
  .hero {
    min-height:100vh;
    display:grid; grid-template-columns:1fr 1fr;
    align-items:center;
    padding:8rem 3rem 6rem;
    position:relative; overflow:hidden;
    background:linear-gradient(135deg, #E8FBF9 0%, #FFF9F0 50%, #FFF0F5 100%);
  }
  .hero::after {
    content:''; position:absolute; inset:0; z-index:0; pointer-events:none;
    background-image:
      radial-gradient(circle at 80% 20%, rgba(11,191,178,0.1) 0%, transparent 40%),
      radial-gradient(circle at 10% 80%, rgba(255,107,107,0.07) 0%, transparent 35%),
      radial-gradient(circle at 55% 65%, rgba(255,224,102,0.08) 0%, transparent 30%);
  }
  .hero-wave { position:absolute; bottom:-1px; left:0; right:0; z-index:1; }
  .hero-left { position:relative; z-index:2; }
  .hero-right { position:relative; z-index:2; display:flex; align-items:center; justify-content:center; }

  .hero-badge {
    display:inline-flex; align-items:center; gap:0.55rem;
    background:rgba(11,191,178,0.1); border:1.5px solid rgba(11,191,178,0.25);
    padding:0.38rem 1rem; border-radius:100px; margin-bottom:1.6rem;
    animation:fadeUp 0.7s ease both;
  }
  .badge-dot { width:7px; height:7px; background:var(--aqua); border-radius:50%; animation:pulse 2s ease-in-out infinite; }
  .badge-text { font-size:0.7rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:var(--aqua); }
  @keyframes pulse { 0%,100%{opacity:1;transform:scale(1)} 50%{opacity:0.5;transform:scale(1.4)} }

  h1 { font-family:'Pacifico',cursive; font-size:clamp(2.8rem,5.5vw,5.4rem); line-height:1.2; color:var(--navy); animation:fadeUp 0.7s 0.08s ease both; }
  h1 .h1-wave { color:var(--aqua); display:block; }
  .hero-sub { margin-top:1.3rem; font-size:1rem; font-weight:400; line-height:1.85; color:var(--muted); max-width:420px; animation:fadeUp 0.7s 0.16s ease both; }

  .hero-hours { margin-top:2rem; display:flex; gap:0.8rem; flex-wrap:wrap; animation:fadeUp 0.7s 0.24s ease both; }
  .hour-pill { background:white; border:1.5px solid var(--line); border-radius:14px; padding:0.7rem 1.2rem; box-shadow:var(--shadow); }
  .hour-day { font-size:0.6rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:var(--coral); margin-bottom:3px; }
  .hour-time { font-size:0.88rem; font-weight:700; color:var(--navy); }

  .hero-actions { margin-top:2rem; display:flex; align-items:center; gap:1.8rem; animation:fadeUp 0.7s 0.32s ease both; }
  .btn-main { font-size:0.78rem; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; padding:0.95rem 2.1rem; background:var(--aqua); color:white; text-decoration:none; border-radius:100px; display:inline-block; box-shadow:0 6px 20px rgba(11,191,178,0.35); transition:background 0.2s, transform 0.2s, box-shadow 0.2s; }
  .btn-main:hover { background:var(--coral); transform:translateY(-2px); box-shadow:0 8px 24px rgba(255,107,107,0.35); }
  .hero-tel { font-size:0.82rem; font-weight:600; color:var(--muted); }
  .hero-tel a { color:var(--navy); text-decoration:none; font-weight:800; transition:color 0.2s; }
  .hero-tel a:hover { color:var(--aqua); }

  /* hero card */
  .hero-card { width:310px; position:relative; animation:fadeUp 0.7s 0.12s ease both; }
  .hero-card::before { content:'🌊'; position:absolute; font-size:1.4rem; top:-14px; right:-8px; animation:float 3s ease-in-out infinite; }
  .hero-card::after  { content:'✨'; position:absolute; font-size:1.1rem; bottom:8px; left:-18px; animation:float 4s ease-in-out infinite 1s; }
  .hci { background:white; border-radius:28px; padding:2.8rem 2.2rem; text-align:center; box-shadow:0 20px 60px rgba(11,191,178,0.14), 0 4px 20px rgba(0,0,0,0.05); position:relative; overflow:hidden; }
  .hci::before { content:''; position:absolute; top:0; left:0; right:0; height:5px; background:linear-gradient(90deg,var(--aqua),var(--coral),var(--lemon)); }
  .hci-icon { font-size:3.6rem; display:block; margin-bottom:1.1rem; }
  .hci-title { font-family:'Pacifico',cursive; font-size:1.45rem; color:var(--navy); margin-bottom:0.25rem; }
  .hci-sub { font-size:0.7rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:var(--aqua); }
  .hci-tags { display:flex; flex-direction:column; gap:0.45rem; margin-top:1.6rem; }
  .hci-tag { display:flex; align-items:center; gap:0.65rem; padding:0.6rem 0.9rem; border-radius:10px; font-size:0.8rem; font-weight:700; color:var(--navy); text-align:left; }
  .hci-tag.t1 { background:var(--mint); }
  .hci-tag.t2 { background:var(--coral-lt); }
  .hci-tag.t3 { background:var(--lemon-lt); }
  .tdot { width:6px; height:6px; border-radius:50%; flex-shrink:0; }
  .tdot.a { background:var(--aqua); } .tdot.c { background:var(--coral); } .tdot.l { background:var(--peach); }

  @keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-8px)} }
  @keyframes fadeUp { from{opacity:0;transform:translateY(20px)} to{opacity:1;transform:none} }

  /* ── SHARED ── */
  section { padding:6rem 3rem; }
  .eyebrow { display:inline-flex; align-items:center; gap:0.55rem; margin-bottom:0.9rem; }
  .eline { width:26px; height:2.5px; border-radius:2px; background:var(--aqua); }
  .eyebrow span { font-size:0.68rem; font-weight:800; letter-spacing:2.5px; text-transform:uppercase; color:var(--aqua); }
  .eyebrow.co .eline { background:var(--coral); }
  .eyebrow.co span { color:var(--coral); }
  h2 { font-family:'Pacifico',cursive; font-size:clamp(2rem,3.5vw,3.2rem); line-height:1.2; color:var(--navy); }
  h2 .aq { color:var(--aqua); } h2 .co { color:var(--coral); }

  /* ── ABOUT ── */
  .about { background:white; display:grid; grid-template-columns:1fr 1fr; gap:5rem; align-items:center; position:relative; overflow:hidden; }
  .about::before { content:''; position:absolute; top:0; left:0; right:0; height:5px; background:linear-gradient(90deg,var(--aqua),var(--lemon),var(--coral)); }
  .about-body { font-size:0.95rem; font-weight:400; line-height:1.85; color:var(--muted); margin-top:1rem; max-width:460px; }
  .about-stats { display:grid; grid-template-columns:1fr 1fr; gap:1rem; margin-top:2.2rem; }
  .astat { background:var(--cream); border:1.5px solid var(--line); border-radius:18px; padding:1.4rem; transition:transform 0.2s, box-shadow 0.2s; }
  .astat:hover { transform:translateY(-3px); box-shadow:var(--shadow); }
  .astat.c { border-color:rgba(255,107,107,0.2); }
  .astat-num { font-family:'Pacifico',cursive; font-size:2.2rem; color:var(--aqua); line-height:1; }
  .astat.c .astat-num { color:var(--coral); }
  .astat-label { font-size:0.76rem; font-weight:600; color:var(--muted); margin-top:0.25rem; line-height:1.4; }
  .about-visual { background:linear-gradient(135deg,var(--aqua-lt),var(--mint)); border-radius:28px; padding:3.5rem 2.5rem; text-align:center; border:1.5px solid rgba(11,191,178,0.18); position:relative; overflow:hidden; }
  .about-visual::after { content:'🌊🌊🌊'; position:absolute; bottom:-14px; left:0; right:0; font-size:4rem; opacity:0.1; letter-spacing:-8px; overflow:hidden; white-space:nowrap; }
  .av-icon { font-size:4.5rem; display:block; margin-bottom:1.2rem; }
  .av-quote { font-family:'Pacifico',cursive; font-size:1.4rem; color:var(--navy); line-height:1.4; }
  .av-quote em { color:var(--aqua); font-style:normal; }

  /* ── MENU ── */
  .menu-sec { background:linear-gradient(160deg, #EBF9FA 0%, var(--cream) 55%); }
  .menu-tabs { display:flex; gap:0.6rem; flex-wrap:wrap; margin:2rem 0 3rem; }
  .tab-btn { font-family:'Nunito',sans-serif; font-size:0.78rem; font-weight:800; letter-spacing:1px; text-transform:uppercase; padding:0.6rem 1.4rem; border-radius:100px; border:2px solid var(--line); background:white; color:var(--muted); cursor:pointer; transition:all 0.2s; }
  .tab-btn:hover, .tab-btn.active { background:var(--aqua); border-color:var(--aqua); color:white; }
  .tab-btn.active.co { background:var(--coral); border-color:var(--coral); }
  .tab-btn.active.pe { background:var(--peach); border-color:var(--peach); }
  .menu-panel { display:none; }
  .menu-panel.active { display:block; }
  .menu-grid { display:grid; grid-template-columns:repeat(auto-fill, minmax(220px, 1fr)); gap:1.2rem; }
  .menu-item { background:white; border-radius:20px; padding:1.5rem 1.4rem; border:1.5px solid rgba(11,191,178,0.1); box-shadow:0 3px 16px rgba(11,191,178,0.07); transition:transform 0.25s, box-shadow 0.25s; position:relative; overflow:hidden; }
  .menu-item::before { content:''; position:absolute; top:0; left:0; right:0; height:3px; background:var(--aqua); }
  .menu-item.co::before { background:var(--coral); }
  .menu-item.pe::before { background:var(--peach); }
  .menu-item:hover { transform:translateY(-4px); box-shadow:0 10px 30px rgba(11,191,178,0.13); }
  .mi-emoji { font-size:1.6rem; display:block; margin-bottom:0.6rem; }
  .mi-name { font-family:'Pacifico',cursive; font-size:1.05rem; color:var(--navy); margin-bottom:0.3rem; line-height:1.3; }
  .mi-desc { font-size:0.78rem; font-weight:400; color:var(--muted); line-height:1.6; }
  .mi-tag { display:inline-block; margin-top:0.7rem; font-size:0.62rem; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; padding:0.25rem 0.7rem; border-radius:100px; background:var(--aqua-lt); color:var(--aqua); }
  .mi-tag.co { background:var(--coral-lt); color:var(--coral); }
  .mi-tag.pe { background:#FFF4EC; color:var(--peach); }
  .menu-note { margin-top:2rem; padding:1.2rem 1.5rem; background:white; border-radius:14px; border:1.5px solid var(--line); font-size:0.85rem; font-weight:600; color:var(--muted); display:flex; align-items:center; gap:0.7rem; }

  /* boosters */
  .booster-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(180px,1fr)); gap:1rem; }
  .booster-card { background:white; border-radius:16px; padding:1.3rem 1.2rem; border:1.5px solid var(--lemon-lt); text-align:center; box-shadow:0 2px 12px rgba(255,224,102,0.15); transition:transform 0.2s; }
  .booster-card:hover { transform:translateY(-3px); }
  .bc-icon { font-size:1.5rem; display:block; margin-bottom:0.4rem; }
  .bc-name { font-size:0.82rem; font-weight:800; color:var(--navy); }
  .bc-desc { font-size:0.72rem; font-weight:400; color:var(--muted); margin-top:0.2rem; line-height:1.4; }

  /* ── DRUMMING CTA BANNER ── */
  .drum-banner {
    background:linear-gradient(135deg,#FFF3EE 0%,#FFFBE0 100%);
    border-top:1px solid rgba(255,107,107,0.12);
    border-bottom:1px solid rgba(255,107,107,0.12);
    padding:3.5rem 3rem;
    display:flex; align-items:center; justify-content:space-between; gap:2rem; flex-wrap:wrap;
  }
  .drum-banner-left { display:flex; align-items:center; gap:1.5rem; }
  .drum-banner-icon { font-size:3rem; animation:bounce 0.9s ease-in-out infinite alternate; }
  @keyframes bounce { from{transform:translateY(0)} to{transform:translateY(-10px)} }
  .drum-banner h3 { font-family:'Pacifico',cursive; font-size:1.6rem; color:var(--navy); margin-bottom:0.3rem; }
  .drum-banner p { font-size:0.88rem; font-weight:400; color:var(--muted); line-height:1.7; max-width:460px; }
  .btn-coral { font-size:0.78rem; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; padding:1rem 2.2rem; background:var(--coral); color:white; text-decoration:none; border-radius:100px; display:inline-block; box-shadow:0 6px 20px rgba(255,107,107,0.35); transition:background 0.2s, transform 0.2s; white-space:nowrap; }
  .btn-coral:hover { background:var(--peach); transform:translateY(-2px); }

  /* ── SHOP ── */
  .shop-sec { background:white; text-align:center; position:relative; overflow:hidden; }
  .shop-sec::before { content:''; position:absolute; top:0; left:0; right:0; height:5px; background:linear-gradient(90deg,var(--aqua),var(--lemon),var(--coral)); }
  .shop-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; max-width:660px; margin:2.5rem auto 0; }
  .shop-card { background:var(--cream); border-radius:24px; padding:2.5rem 1.8rem; text-decoration:none; display:block; border:1.5px solid var(--line); position:relative; overflow:hidden; transition:transform 0.25s, box-shadow 0.25s; }
  .shop-card::before { content:''; position:absolute; top:0; left:0; right:0; height:4px; background:var(--aqua); }
  .shop-card.s2::before { background:var(--coral); }
  .shop-card:hover { transform:translateY(-5px); box-shadow:0 14px 36px rgba(11,191,178,0.12); }
  .shop-card.s2:hover { box-shadow:0 14px 36px rgba(255,107,107,0.12); }
  .s-init { width:54px; height:54px; background:var(--aqua-lt); border-radius:50%; display:flex; align-items:center; justify-content:center; font-family:'Pacifico',cursive; font-size:1.35rem; color:var(--aqua); margin:0 auto 1.2rem; border:2px solid rgba(11,191,178,0.2); }
  .shop-card.s2 .s-init { background:var(--coral-lt); color:var(--coral); border-color:rgba(255,107,107,0.2); }
  .shop-card h3 { font-family:'Pacifico',cursive; font-size:1.25rem; color:var(--navy); margin-bottom:0.35rem; }
  .shop-card p { font-size:0.8rem; font-weight:400; color:var(--muted); line-height:1.6; }
  .s-link { display:inline-flex; align-items:center; gap:0.3rem; margin-top:1.2rem; font-size:0.7rem; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; color:var(--aqua); }
  .shop-card.s2 .s-link { color:var(--coral); }

  /* ── CONNECT ── */
  .connect { background:linear-gradient(135deg,#1A3A35 0%,#0F2A25 100%); text-align:center; position:relative; overflow:hidden; }
  .connect::before { content:''; position:absolute; inset:0; background:radial-gradient(ellipse 70% 60% at 50% 0%,rgba(11,191,178,0.1),transparent 60%); pointer-events:none; }
  .connect h2 { color:white; }
  .connect h2 .aq { color:var(--aqua); }
  .connect .eyebrow .eline { background:var(--aqua); }
  .connect .eyebrow span { color:var(--aqua); }
  .connect-sub { font-size:0.92rem; font-weight:400; line-height:1.85; color:rgba(255,255,255,0.5); max-width:400px; margin:1rem auto 3rem; }
  .social-grid { display:flex; gap:1rem; justify-content:center; flex-wrap:wrap; }
  .social-btn { display:flex; align-items:center; gap:0.65rem; padding:0.85rem 1.6rem; background:rgba(255,255,255,0.07); border:1.5px solid rgba(255,255,255,0.12); border-radius:100px; text-decoration:none; color:rgba(255,255,255,0.65); font-size:0.7rem; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; transition:all 0.2s; }
  .social-btn:hover { background:var(--aqua); border-color:var(--aqua); color:white; transform:translateY(-2px); }
  .social-btn svg { width:13px; height:13px; fill:currentColor; flex-shrink:0; }

  /* ── FOOTER ── */
  footer { background:#0A1F1B; padding:2rem 3rem; display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:1rem; border-top:1px solid rgba(255,255,255,0.06); }
  .footer-logo { font-family:'Pacifico',cursive; font-size:1.1rem; color:var(--aqua); text-decoration:none; }
  .footer-logo span { color:var(--coral); }
  .footer-links { display:flex; gap:1.5rem; flex-wrap:wrap; }
  .footer-links a { font-size:0.7rem; font-weight:600; color:rgba(255,255,255,0.35); text-decoration:none; letter-spacing:1px; transition:color 0.2s; }
  .footer-links a:hover { color:var(--aqua); }
  .footer-info { font-size:0.7rem; font-weight:600; color:rgba(255,255,255,0.22); letter-spacing:0.5px; text-align:center; }
  .footer-tel a { color:var(--aqua); text-decoration:none; }

  /* ── REVEAL ── */
  .reveal { opacity:0; transform:translateY(22px); transition:opacity 0.75s ease, transform 0.75s ease; }
  .reveal.visible { opacity:1; transform:none; }
  .d1{transition-delay:0.1s} .d2{transition-delay:0.2s} .d3{transition-delay:0.3s}

  /* ── RESPONSIVE ── */
  @media (max-width:960px) {
    .hero, .about { grid-template-columns:1fr; gap:3rem; }
    .hero { text-align:center; padding:7rem 1.8rem 4rem; }
    .hero-badge, .hero-hours, .hero-actions { justify-content:center; }
    .hero-sub { margin:1rem auto 0; }
    .hero-card { max-width:310px; margin:0 auto; }
    nav { padding:1rem 1.5rem; }
    .nav-links { display:none; }
    .hamburger { display:flex; }
    section { padding:4.5rem 1.8rem; }
    footer { padding:1.5rem 1.8rem; }
    .drum-banner { flex-direction:column; text-align:center; }
    .drum-banner-left { flex-direction:column; gap:0.8rem; }
  }
  @media (max-width:600px) {
    .shop-grid { grid-template-columns:1fr; max-width:320px; }
    footer { flex-direction:column; text-align:center; }
    .footer-links { justify-content:center; }
  }
</style>

</head>
<body>

<!-- NAV -->

<nav>
  <a href="index.html" class="nav-logo">New <span>Wave</span> Nutrition</a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#menu">Menu</a></li>
    <li><a href="drumming.html">Classes</a></li>
    <li><a href="#shop">Shop</a></li>
    <li><a href="#connect">Connect</a></li>
    <li><a href="drumming.html" class="nav-cta">Book a Class</a></li>
  </ul>
  <button class="hamburger" aria-label="Menu" onclick="toggleMenu(this)">
    <span></span><span></span><span></span>
  </button>
</nav>

<div class="mobile-nav" id="mobileNav">
  <a href="#about" onclick="closeMobileNav()">About</a>
  <a href="#menu" onclick="closeMobileNav()">Menu</a>
  <a href="drumming.html">Classes</a>
  <a href="#shop" onclick="closeMobileNav()">Shop</a>
  <a href="#connect" onclick="closeMobileNav()">Connect</a>
  <a href="drumming.html">Book a Class 🥁</a>
</div>

<!-- HERO -->

<section class="hero">
  <div class="hero-left">
    <div class="hero-badge">
      <div class="badge-dot"></div>
      <span class="badge-text">Palm Harbor, FL · 1330 Tampa Rd</span>
    </div>
    <h1>Fuel Your<br><span class="h1-wave">New Wave</span></h1>
    <p class="hero-sub">Handcrafted protein shakes and loaded teas made fresh to order — clean nutrition, big flavor, good vibes only. 🌊</p>
    <div class="hero-hours">
      <div class="hour-pill">
        <div class="hour-day">Mon – Fri</div>
        <div class="hour-time">7:00 AM – 4:00 PM</div>
      </div>
      <div class="hour-pill">
        <div class="hour-day">Sat – Sun</div>
        <div class="hour-time">9:00 AM – 12:00 PM</div>
      </div>
      <div class="hour-pill">
        <div class="hour-day">Delivery</div>
        <div class="hour-time">Wed & Fri 10–2</div>
      </div>
    </div>
    <div class="hero-actions">
      <a href="#menu" class="btn-main">See the Menu</a>
      <span class="hero-tel">Call ahead: <a href="tel:7277545124">(727) 754-5124</a></span>
    </div>
  </div>

  <div class="hero-right">
    <div class="hero-card">
      <div class="hci">
        <span class="hci-icon">🥤</span>
        <div class="hci-title">Shake & Tea Bar</div>
        <div class="hci-sub">Made fresh daily</div>
        <div class="hci-tags">
          <div class="hci-tag t1"><span class="tdot a"></span>Protein Shakes</div>
          <div class="hci-tag t2"><span class="tdot c"></span>Loaded Teas</div>
          <div class="hci-tag t3"><span class="tdot l"></span>Energy Boosters</div>
        </div>
      </div>
    </div>
  </div>

  <svg class="hero-wave" viewBox="0 0 1440 64" fill="none" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
    <path d="M0,32 C240,64 480,0 720,32 C960,64 1200,0 1440,32 L1440,64 L0,64 Z" fill="#FFFDF8"/>
  </svg>
</section>

<!-- ABOUT -->

<section class="about" id="about">
  <div class="reveal">
    <div class="eyebrow"><div class="eline"></div><span>Who We Are</span></div>
    <h2>More Than a<br><span class="aq">Shake Shop</span></h2>
    <p class="about-body">New Wave Nutrition is Palm Harbor's community-first nutrition club powered by Herbalife. Whether you're fueling a workout, managing your weight, or just craving something clean and delicious — we pour good vibes into every single cup.</p>
    <p class="about-body" style="margin-top:0.8rem;">Stop in for quick pick-up or call ahead — we also offer delivery on Wednesdays and Fridays from 10–2.</p>
    <div class="about-stats">
      <div class="astat"><div class="astat-num">20+</div><div class="astat-label">Shake & Tea Flavors</div></div>
      <div class="astat c"><div class="astat-num">0</div><div class="astat-label">Artificial Ingredients</div></div>
      <div class="astat"><div class="astat-num">6</div><div class="astat-label">Days Open Every Week</div></div>
      <div class="astat c"><div class="astat-num">∞</div><div class="astat-label">Good Vibes Always</div></div>
    </div>
  </div>
  <div class="reveal d2">
    <div class="about-visual">
      <span class="av-icon">🌊</span>
      <div class="av-quote">Real nutrition,<br><em>real results</em></div>
    </div>
  </div>
</section>

<!-- MENU -->

<section class="menu-sec" id="menu">
  <div class="reveal">
    <div class="eyebrow"><div class="eline"></div><span>What We Serve</span></div>
    <h2>The <span class="aq">Menu</span></h2>
  </div>

  <div class="menu-tabs reveal d1">
    <button class="tab-btn active" onclick="showTab('shakes',this)">🥤 Protein Shakes</button>
    <button class="tab-btn" onclick="showTab('teas',this)">🍵 Loaded Teas</button>
    <button class="tab-btn" onclick="showTab('boosters',this)">⚡ Boosters & Add-ons</button>
  </div>

  <!-- SHAKES -->

  <div class="menu-panel active" id="tab-shakes">
    <div class="menu-grid reveal">
      <div class="menu-item"><span class="mi-emoji">🍫</span><div class="mi-name">Chocolate Dream</div><div class="mi-desc">Rich, creamy chocolate — the classic that never gets old. High protein, low sugar.</div><span class="mi-tag">Fan Favorite</span></div>
      <div class="menu-item"><span class="mi-emoji">🍓</span><div class="mi-name">Strawberry Bliss</div><div class="mi-desc">Fresh strawberry flavor packed with protein. Light, fruity, and totally satisfying.</div><span class="mi-tag">Bestseller</span></div>
      <div class="menu-item"><span class="mi-emoji">🍋</span><div class="mi-name">Lemon Drop</div><div class="mi-desc">Bright, zesty citrus with a creamy finish. A fan fave we love to bring back.</div><span class="mi-tag">Seasonal</span></div>
      <div class="menu-item"><span class="mi-emoji">🌿</span><div class="mi-name">Mint Extreme</div><div class="mi-desc">Cool mint meets cookies & cream for a refreshing, indulgent treat.</div><span class="mi-tag">Shake of the Month ⭐</span></div>
      <div class="menu-item"><span class="mi-emoji">🥭</span><div class="mi-name">Mango Tango</div><div class="mi-desc">Tropical mango vibes in every sip. Fruity, creamy, and totally addictive.</div><span class="mi-tag">Tropical 🌴</span></div>
      <div class="menu-item"><span class="mi-emoji">🎂</span><div class="mi-name">Birthday Cake</div><div class="mi-desc">Funfetti flavor in shake form. Sweet, celebratory, and packed with protein.</div><span class="mi-tag">Limited Pop-Up</span></div>
      <div class="menu-item"><span class="mi-emoji">🍑</span><div class="mi-name">Peaches & Cream</div><div class="mi-desc">Sweet peach blended with creamy Herbalife protein. Summer in a cup.</div><span class="mi-tag">Summer Fave</span></div>
      <div class="menu-item"><span class="mi-emoji">☕</span><div class="mi-name">Mocha Madness</div><div class="mi-desc">Coffee + chocolate. Your morning fuel upgraded with a protein punch.</div><span class="mi-tag">Morning Boost</span></div>
      <div class="menu-item"><span class="mi-emoji">🍪</span><div class="mi-name">Cookies & Cream</div><div class="mi-desc">Oreo-inspired bliss. Tastes like dessert, fuels like a meal.</div><span class="mi-tag">Fan Favorite</span></div>
      <div class="menu-item"><span class="mi-emoji">🍌</span><div class="mi-name">Banana Foster</div><div class="mi-desc">Creamy banana with a hint of caramel warmth. Smooth, rich, guilt-free.</div><span class="mi-tag">House Special</span></div>
      <div class="menu-item"><span class="mi-emoji">🥜</span><div class="mi-name">PB Power</div><div class="mi-desc">Peanut butter protein packed — thick, nutty, and ridiculously filling.</div><span class="mi-tag">High Protein</span></div>
      <div class="menu-item"><span class="mi-emoji">✨</span><div class="mi-name">Shake of the Month</div><div class="mi-desc">A rotating monthly special created by our coaches. Always a surprise — always amazing.</div><span class="mi-tag">Ask Us!</span></div>
    </div>
    <div class="menu-note reveal">💡 All shakes are made with Herbalife Formula 1 — high-protein, low-calorie meal replacements. Fully customizable. Just ask a coach!</div>
  </div>

  <!-- TEAS -->

  <div class="menu-panel" id="tab-teas">
    <div class="menu-grid reveal">
      <div class="menu-item co"><span class="mi-emoji">🍊</span><div class="mi-name">Summer Splash</div><div class="mi-desc">Orange base · Caffeine · B & C Vitamins · Red & Blue Raspberry. Pure sunshine in a cup.</div><span class="mi-tag co">Seasonal</span></div>
      <div class="menu-item co"><span class="mi-emoji">🥭</span><div class="mi-name">Mango Paradise</div><div class="mi-desc">Mango + peach over house metabolism-booster tea. Like sitting on a tropical island.</div><span class="mi-tag co">Tropical 🌴</span></div>
      <div class="menu-item co"><span class="mi-emoji">🍓</span><div class="mi-name">Strawberry Surf</div><div class="mi-desc">Sweet strawberry tea bomb loaded with antioxidants and natural energy. Zero sugar.</div><span class="mi-tag co">Bestseller</span></div>
      <div class="menu-item co"><span class="mi-emoji">🍷</span><div class="mi-name">The Wine-Oh</div><div class="mi-desc">Such a hit we made it permanent. A sophisticated berry blend that hits just right.</div><span class="mi-tag co">Fan Favorite</span></div>
      <div class="menu-item co"><span class="mi-emoji">🍋</span><div class="mi-name">Lemon Squeeze</div><div class="mi-desc">Tart citrus meets sweet tea. Crisp, hydrating, and endlessly refreshing.</div><span class="mi-tag co">Refreshing</span></div>
      <div class="menu-item co"><span class="mi-emoji">🫐</span><div class="mi-name">Blue Lagoon</div><div class="mi-desc">Blue raspberry over house tea. Vibrant color, bold flavor, metabolism boost.</div><span class="mi-tag co">House Special</span></div>
      <div class="menu-item co"><span class="mi-emoji">🍑</span><div class="mi-name">Peach Perfect</div><div class="mi-desc">Sweet peach over digestive-support house tea. Light, fruity, feel-good fuel.</div><span class="mi-tag co">Popular</span></div>
      <div class="menu-item co"><span class="mi-emoji">💣</span><div class="mi-name">Tea Bomb of the Month</div><div class="mi-desc">A brand-new flavor bomb each month. Come in and ask what's dropping!</div><span class="mi-tag co">Ask Us!</span></div>
    </div>
    <div class="menu-note reveal">🌿 All loaded teas use Herbalife Liftoff & tea concentrate. Zero sugar · Antioxidants · Vitamins B & C · Metabolism support. Available in 24oz & 32oz.</div>
  </div>

  <!-- BOOSTERS -->

  <div class="menu-panel" id="tab-boosters">
    <div class="booster-grid reveal">
      <div class="booster-card"><span class="bc-icon">💧</span><div class="bc-name">Aloe</div><div class="bc-desc">Hydration + digestive support</div></div>
      <div class="booster-card"><span class="bc-icon">🔥</span><div class="bc-name">Metabolism Booster</div><div class="bc-desc">Rev up your burn all day</div></div>
      <div class="booster-card"><span class="bc-icon">🛡️</span><div class="bc-name">Immunity Support</div><div class="bc-desc">Vitamin C & zinc boost</div></div>
      <div class="booster-card"><span class="bc-icon">⚡</span><div class="bc-name">Energy Shot</div><div class="bc-desc">Clean caffeine, no crash</div></div>
      <div class="booster-card"><span class="bc-icon">✨</span><div class="bc-name">Collagen</div><div class="bc-desc">Skin, hair & joint support</div></div>
      <div class="booster-card"><span class="bc-icon">🌿</span><div class="bc-name">Probiotics</div><div class="bc-desc">Gut health & digestion</div></div>
      <div class="booster-card"><span class="bc-icon">🌾</span><div class="bc-name">Fiber Blend</div><div class="bc-desc">Keeps you full longer</div></div>
      <div class="booster-card"><span class="bc-icon">💊</span><div class="bc-name">Electrolytes</div><div class="bc-desc">Rehydrate & replenish</div></div>
    </div>
    <div class="menu-note reveal">✅ Mix and match any booster into your shake or tea. Ask a coach to help build your perfect custom drink!</div>
  </div>
</section>

<!-- DRUMMING BANNER -->

<div class="drum-banner reveal">
  <div class="drum-banner-left">
    <span class="drum-banner-icon">🥁</span>
    <div>
      <h3>Cardio Drumming Classes</h3>
      <p>The most fun cardio class you'll ever take — drumsticks, big balls, live music. No experience needed. All levels welcome. Book your spot on Mindbody.</p>
    </div>
  </div>
  <a href="drumming.html" class="btn-coral">Learn More & Book →</a>
</div>

<!-- SHOP -->

<section class="shop-sec" id="shop">
  <div class="reveal">
    <div class="eyebrow" style="justify-content:center;"><div class="eline"></div><span>Herbalife Products</span></div>
    <h2>Shop With Our <span class="aq">Coaches</span></h2>
  </div>
  <p style="font-size:0.92rem;font-weight:400;color:var(--muted);max-width:400px;margin:0.9rem auto 0;line-height:1.85;" class="reveal d1">Bring New Wave home. Shop Herbalife products directly through Nikki or Lisa.</p>
  <div class="shop-grid">
    <a href="http://newwave.herbalife.com/en-us/u" class="shop-card reveal" target="_blank" rel="noopener">
      <div class="s-init">N</div>
      <h3>Shop with Nikki</h3>
      <p>Official New Wave Nutrition Herbalife storefront</p>
      <span class="s-link">Shop Now →</span>
    </a>
    <a href="https://ldell.goherbalife.com/Catalog/Home/Index/en-US" class="shop-card s2 reveal d1" target="_blank" rel="noopener">
      <div class="s-init">L</div>
      <h3>Shop with Lisa</h3>
      <p>Lisa's personal Herbalife product catalog</p>
      <span class="s-link">Shop Now →</span>
    </a>
  </div>
</section>

<!-- CONNECT -->

<section class="connect" id="connect">
  <div class="reveal">
    <div class="eyebrow" style="justify-content:center;"><div class="eline"></div><span>Stay Connected</span></div>
    <h2>Follow the <span class="aq">Wave</span></h2>
  </div>
  <p class="connect-sub reveal d1">Daily specials, new flavors, class updates, and community moments — follow us so you never miss a drop.</p>
  <div class="social-grid reveal d2">
    <a href="https://www.facebook.com/newwavetampabay/" class="social-btn" target="_blank" rel="noopener" aria-label="Facebook">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
      Facebook
    </a>
    <a href="https://www.instagram.com/new.wave.nutrition/" class="social-btn" target="_blank" rel="noopener" aria-label="Instagram">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
      Instagram
    </a>
    <a href="https://www.tiktok.com/@newwavenutrition" class="social-btn" target="_blank" rel="noopener" aria-label="TikTok">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/></svg>
      TikTok
    </a>
    <a href="tel:7277545124" class="social-btn" aria-label="Call us">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
      (727) 754-5124
    </a>
  </div>
</section>

<footer>
  <a href="index.html" class="footer-logo">New <span>Wave</span> Nutrition</a>
  <div class="footer-info">1330 Tampa Rd · Palm Harbor, FL 34683 · Mon–Fri 7–4 · Sat–Sun 9–12 · Delivery Wed & Fri 10–2</div>
  <div class="footer-links">
    <a href="#menu">Menu</a>
    <a href="drumming.html">Classes</a>
    <a href="#shop">Shop</a>
    <a href="#connect">Contact</a>
    <a href="tel:7277545124">(727) 754-5124</a>
  </div>
</footer>

<script>
  function showTab(id, btn) {
    document.querySelectorAll('.menu-panel').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active','co','pe'));
    document.getElementById('tab-'+id).classList.add('active');
    btn.classList.add('active');
    if (id==='teas') btn.classList.add('co');
    if (id==='boosters') btn.classList.add('pe');
    document.querySelectorAll('#tab-'+id+' .reveal').forEach(el => el.classList.add('visible'));
  }

  function toggleMenu(btn) {
    btn.classList.toggle('open');
    document.getElementById('mobileNav').classList.toggle('open');
  }
  function closeMobileNav() {
    document.getElementById('mobileNav').classList.remove('open');
    document.querySelector('.hamburger').classList.remove('open');
  }

  const obs = new IntersectionObserver(entries => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.08 });
  document.querySelectorAll('.reveal').forEach(el => obs.observe(el));
</script>

</body>
</html># Newwavenutrition
