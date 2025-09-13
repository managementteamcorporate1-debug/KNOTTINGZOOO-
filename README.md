<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>KNOTTINGZOO — Hot Dog Content on Telegram</title>
  <meta name="description" content="KNOTTINGZOO — hottest dog photos, videos, tips and premium services on Telegram." />
  <!-- Open Graph -->
  <meta property="og:title" content="KNOTTINGZOO" />
  <meta property="og:description" content="Join KNOTTINGZOO on Telegram for hot dog content: photos, videos, VIP packs and custom requests." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=KNOTTINGZOO" />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#ff6b6b" />

  <style>
    :root{
      --accent:#ff6b6b;
      --muted:#6b6b6b;
      --bg:#0f1720;
      --card:#0b1220;
      --glass: rgba(255,255,255,0.03);
      --radius:14px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    html,body{height:100%;margin:0;background:
      linear-gradient(180deg,#071020 0%, #081226 40%, #021018 100%); color:#e8eef6;}

    .wrap{max-width:980px;margin:28px auto;padding:20px;}

    header{display:flex;gap:16px;align-items:center;}
    .logo{
      width:84px;height:84px;border-radius:18px;background:linear-gradient(135deg,var(--accent),#ffb86b);
      display:flex;align-items:center;justify-content:center;font-weight:700;color:#111;font-size:20px;box-shadow:0 8px 30px rgba(0,0,0,0.6);
    }
    h1{margin:0;font-size:28px;}
    p.lead{color:var(--muted);margin-top:6px;margin-bottom:18px;}

    .hero{
      display:flex;gap:18px;align-items:center;flex-wrap:wrap;margin-top:12px;
    }

    .cta{
      display:flex;gap:10px;align-items:center;margin-top:8px;
    }
    a.btn{
      display:inline-flex;gap:10px;align-items:center;padding:12px 16px;border-radius:12px;text-decoration:none;font-weight:600;
      background:linear-gradient(90deg,var(--accent),#ff9a9a);color:#071020;box-shadow:0 8px 28px rgba(255,107,107,0.12);
    }
    a.btn.ghost{background:transparent;color:#e8eef6;border:1px solid rgba(255,255,255,0.06);}

    .cards{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-top:20px;}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:12px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,12,0.6);overflow:hidden;}
    .card img{width:100%;height:160px;object-fit:cover;border-radius:10px;}
    .meta{display:flex;justify-content:space-between;align-items:center;margin-top:10px;}
    .tag{background:rgba(255,255,255,0.04);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted);}

    .services{display:grid;grid-template-columns:1fr;gap:12px;margin-top:18px;}
    .service{background:var(--card);padding:14px;border-radius:12px;display:flex;gap:12px;align-items:flex-start;}
    .service .ico{width:48px;height:48px;border-radius:12px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);font-size:20px;}
    .service h4{margin:0;font-size:16px;}
    .service p{margin:6px 0 0;color:var(--muted);font-size:14px;}

    footer{margin-top:28px;padding:18px;border-radius:12px;background:transparent;color:var(--muted);font-size:13px;text-align:center;}
    @media(max-width:720px){
      .cards{grid-template-columns:1fr;}
      header{gap:12px;}
      .logo{width:68px;height:68px;}
    }

    /* small QR + quick links row */
    .row{display:flex;gap:12px;align-items:center;margin-top:12px;flex-wrap:wrap;}
    .qr{width:110px;height:110px;border-radius:12px;background:#fff;display:flex;align-items:center;justify-content:center;overflow:hidden;}
    .qr img{width:100%;height:100%;object-fit:cover;}
    .links{display:flex;flex-direction:column;gap:8px;}
    .small-btn{padding:8px 12px;border-radius:10px;text-decoration:none;background:rgba(255,255,255,0.03);color:#e8eef6;font-weight:600;border:1px solid rgba(255,255,255,0.03);display:inline-block;}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">KZ</div>
      <div>
        <h1>KNOTTINGZOO</h1>
        <p class="lead">Join our Telegram channel for the hottest dog photos, videos, exclusive VIP packs and custom requests.</p>
        <div class="cta">
          <!-- Replace the links below with your channel and bot -->
          <a class="btn" href="https://t.me/KNOTTINGZOOO" target="_blank" rel="noopener noreferrer">
            ▶ Join Channel
          </a>
          <a class="btn ghost" href="https://t.me/KNOTTINGZOO_bot" target="_blank" rel="noopener noreferrer">
            🤖 Chat / Subscribe Bot
          </a>
        </div>
      </div>
    </header>

    <section class="hero">
      <div style="flex:1;min-width:260px;">
        <div class="cards" id="latestCards">
          <!-- Example post cards; replace images and captions with real content -->
          <div class="card">
            <img src="https://images.unsplash.com/photo-1517849845537-4d257902454a?q=80&w=1200&auto=format&fit=crop&crop=faces" alt="Dog 1">
            <div class="meta">
              <div>
                <strong>Fluffy afternoon</strong>
                <div style="font-size:13px;color:var(--muted);">Cute pup compilation • 1.2K views</div>
              </div>
              <div class="tag">Free</div>
            </div>
          </div>

          <div class="card">
            <img src="https://images.unsplash.com/photo-1507149833265-60c372daea22?q=80&w=1200&auto=format&fit=crop&crop=faces" alt="Dog 2">
            <div class="meta">
              <div>
                <strong>Puppy tricks</strong>
                <div style="font-size:13px;color:var(--muted);">Short video • 980 views</div>
              </div>
              <div class="tag">Video</div>
            </div>
          </div>
        </div>

        <div class="row" style="margin-top:12px;">
          <div class="qr" title="Open channel in Telegram">
            <!-- Simple QR placeholder - replace with a generated QR if you'd like -->
            <img alt="QR" src="https://via.placeholder.com/300.png?text=QR+KNOTTINGZOO">
          </div>
          <div class="links">
            <a class="small-btn" href="https://t.me/KNOTTINGZOOO" target="_blank">Open Channel • t.me/KNOTTINGZOO</a>
            <a class="small-btn" href="https://t.me/+yourInviteLinkHere" target="_blank">Join via invite link</a>
            <a class="small-btn" href="mailto:owner@example.com">Contact Owner</a>
          </div>
        </div>
      </div>

      <aside style="width:320px;min-width:260px;">
        <div class="services">
          <div class="service">
            <div class="ico">💎</div>
            <div>
              <h4>VIP Packs (Paid)</h4>
              <p>High-res photo packs, exclusive videos and behind-the-scenes content. Payment via crypto / gift cards. Link & instructions inside the channel.</p>
              <div style="margin-top:8px;">
                <a href="#" class="small-btn" onclick="alert('Replace this with your payment/checkout flow')">Buy VIP Pack</a>
              </div>
            </div>
          </div>

          <div class="service">
            <div class="ico">📨</div>
            <div>
              <h4>Request Custom Content</h4>
              <p>Want a custom shoot or themed pack? Send a request via the bot or DM in Telegram.</p>
              <div style="margin-top:8px;">
                <a class="small-btn" href="https://t.me/KNOTTINGZOOO_bot" target="_blank">Make a Request</a>
              </div>
            </div>
          </div>

          <div class="service">
            <div class="ico">🔒</div>
            <div>
              <h4>Private Collections</h4>
              <p>Locked albums for subscribers only. Automate access with our subscription bot or manual add-on.</p>
            </div>
          </div>
        </div>

        <div style="margin-top:12px;background:rgba(255,255,255,0.02);padding:12px;border-radius:12px;">
          <h4 style="margin:0 0 8px 0;">Quick actions</h4>
          <a class="small-btn" href="tg://resolve?domain=KNOTTINGZOOO" style="display:block;margin-bottom:8px;">Open in Telegram App</a>
          <a class="small-btn" href="https://t.me/KNOTTINGZOOO" target="_blank" style="display:block;margin-bottom:8px;">Open in Web Telegram</a>
          <a class="small-btn" href="#" style="display:block;" onclick="navigator.clipboard?.writeText('https://t.me/KNOTTINGZOOO') || alert('Copy link: https://t.me/KNOTTINGZOOO')">Copy Channel Link</a>
        </div>
      </aside>
    </section>

    <section style="margin-top:18px;">
      <h3 style="margin:0 0 8px 0;">How to use this page</h3>
      <ul style="color:var(--muted);line-height:1.6">
        <li>Replace <code>https://t.me/KNOTTINGZOOO</code> and bot links with your actual Telegram channel/bot links if different.</li>
        <li>Replace placeholder images with your own hosted images or file links (use HTTPS).</li>
        <li>To show dynamic latest posts, you can embed Telegram post screenshots or use the Telegram API + a small backend to fetch latest messages.</li>
      </ul>
    </section>

    <footer>
      © <span id="year"></span> KNOTTINGZOOO— By joining you accept the channel rules. Content is for adults where applicable. Not affiliated with Telegram.
    </footer>
  </div>

  <script>
    // small client-side helpers — change or remove as needed
    document.getElementById('year').textContent = new Date().getFullYear();

    // Example: populate more post cards dynamically (placeholder)
    const latest = [
      {title:'Golden Hour Pup',img:'https://images.unsplash.com/photo-1518717758536-85ae29035b6d?q=80&w=1200&auto=format&fit=crop&crop=faces',tag:'Free',meta:'Photo • 430 views'},
      {title:'Silly Zoomies',img:'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop&crop=faces',tag:'Video',meta:'Clip • 2.1K views'}
    ];

    const container = document.getElementById('latestCards');
    latest.forEach(item => {
      const card = document.createElement('div');
      card.className = 'card';
      card.innerHTML = `
        <img src="${item.img}" alt="${item.title}">
        <div class="meta">
          <div>
            <strong>${item.title}</strong>
            <div style="font-size:13px;color:var(--muted);">${item.meta}</div>
          </div>
          <div class="tag">${item.tag}</div>
        </div>
      `;
      container.appendChild(card);
    });
  </script>
</body>
</html>
