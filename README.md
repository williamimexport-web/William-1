
<img width="1024" height="1536" alt="DB7C2529-EE32-4B53-A04F-339D6D90893B" src="https://github.com/user-attachments/assets/9390def7-d058-45f8-96e7-3b236dced9af" />
<!doctype html>
<html lang="en" dir="ltr">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>William Imex — Coming Soon</title>
<meta name="description" content="William Imex — Import & Export | Global shipping between China, Germany, Lebanon and Syria. Coming soon."/>
<link rel="icon" href="" />
<style>
  /* Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&family=Cairo:wght@400;600;700&display=swap');

  :root{
    --gold: #d4af37;
    --muted: #cfcfcf;
    --bg-dark: #070707;
  }
  html,body{height:100%;margin:0;font-family:"Poppins", "Cairo", sans-serif;background:var(--bg-dark);color:#fff;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
  /* background image (file to upload as background.png) */
  body::before{
    content:"";
    position:fixed;inset:0;
    background: center/cover no-repeat url('background.png');
    filter:brightness(.35) contrast(.95);
    z-index:0;
  }
  .wrap{position:relative;z-index:1;min-height:100%;display:flex;align-items:center;justify-content:center;padding:42px;}
  .card{max-width:1100px;width:100%;background:linear-gradient(180deg, rgba(0,0,0,0.20), rgba(0,0,0,0.40));border-radius:12px;padding:46px;border:1px solid rgba(212,175,55,0.06);box-shadow:0 20px 60px rgba(0,0,0,0.6);}
  .grid{display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:center;}
  .brand h1{margin:0;font-size:52px;letter-spacing:3px;color:var(--gold);font-weight:800;text-transform:uppercase;text-shadow:0 6px 20px rgba(0,0,0,0.6);}
  .brand .tag{color:var(--muted);margin-top:10px;font-size:18px;}
  .brand .coming{margin-top:22px;font-size:36px;color:var(--gold);font-weight:700;text-shadow:0 4px 18px rgba(212,175,55,0.25)}
  .brand .sub{margin-top:14px;color:#e6e6e6;font-size:16px;line-height:1.6;max-width:720px}
  .countries{margin-top:18px;color:var(--gold);font-weight:600;letter-spacing:1px}
  .side{background:rgba(255,255,255,0.02);padding:22px;border-radius:10px;border:1px solid rgba(212,175,55,0.04);}
  .side h3{margin:0;color:var(--gold);font-size:18px}
  .side p{color:#ddd;margin:10px 0 0;line-height:1.45}
  .contact-line{margin-top:12px;font-size:15px;color:var(--muted)}
  .contact-line a{color:var(--gold);text-decoration:none}
  .services{margin-top:14px;padding:10px;background:rgba(0,0,0,0.15);border-radius:8px;color:#ddd}
  .footer{margin-top:18px;text-align:center;color:#bfbfbf;font-size:13px}
  /* countdown */
  .countdown{display:flex;gap:10px;margin-top:16px;align-items:center}
  .countdown .box{background:rgba(0,0,0,0.45);padding:10px 12px;border-radius:8px;border:1px solid rgba(255,255,255,0.02);min-width:64px;text-align:center}
  .countdown .num{font-weight:700;color:var(--gold);font-size:20px}
  .countdown .lbl{font-size:11px;color:#ddd;margin-top:4px}

  @media(max-width:880px){
    .grid{grid-template-columns:1fr}
    .brand h1{font-size:38px}
    .brand .coming{font-size:26px}
    .card{padding:26px}
    .side{order:2}
  }
</style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="main" aria-labelledby="title">
      <div class="grid">
        <div class="brand" id="title">
          <!-- optional small logo image if you want: <img src="logo.png" alt="William Imex" style="width:120px;margin-bottom:18px"> -->
          <h1>William Imex</h1>
          <div class="tag">Import &amp; Export — Shipping &amp; Logistics</div>

          <div class="coming">🚀 Coming Soon — قريبًا يفتتح الموقع</div>

          <p class="sub">
            We are building our new website to support global import & export operations.
            <br>
            Global trade & shipping between <strong>China</strong>, <strong>Germany</strong>, <strong>Lebanon</strong> and <strong>Syria</strong>.
            <br><br>
            نحن نعمل على إطلاق موقعنا قريبًا — خدمات الشحن والاستيراد والتصدير بين الصين، ألمانيا، لبنان، وسوريا.
          </p>

          <div class="countries">China · Germany · Lebanon · Syria</div>

          <div class="countdown" aria-hidden="true">
            <div class="box"><div class="num" id="days">00</div><div class="lbl">Days</div></div>
            <div class="box"><div class="num" id="hours">00</div><div class="lbl">Hours</div></div>
            <div class="box"><div class="num" id="minutes">00</div><div class="lbl">Minutes</div></div>
            <div class="box"><div class="num" id="seconds">00</div><div class="lbl">Seconds</div></div>
          </div>

        </div>

        <aside class="side" aria-label="Contact & Services">
          <h3>Contact</h3>
          <p class="contact-line">📍 <strong>Lebanon</strong> | <strong>Germany</strong></p>
          <p class="contact-line">📞 Lebanon: <strong>+961 81858968</strong><br>📞 Germany: <strong>+49 15511334369</strong></p>
          <p class="contact-line">✉️ <a href="mailto:williamimex@outlook.com">williamimex@outlook.com</a></p>

          <div class="services">
            <strong style="color:var(--gold)">Our Services</strong>
            <ul style="margin:10px 0 0 16px;padding:0;color:#ddd">
              <li>International Freight — Air / Sea / Road</li>
              <li>Customs clearance & documentation</li>
              <li>Supplier sourcing (China & Asia)</li>
              <li>Logistics to Lebanon, Syria & Germany</li>
            </ul>
          </div>

          <div style="margin-top:12px;color:var(--muted);font-size:13px">
            Alibaba profile available — Contact for quotes and supplier introductions.
          </div>
        </aside>
      </div>

      <div class="footer">
        <div><strong>William Imex</strong> — Import & Export Services</div>
        <div>© <span id="year"></span> William Imex — All rights reserved.</div>
      </div>
    </div>
  </div>

<script>
  // set year
  document.getElementById('year').textContent = new Date().getFullYear();

  // countdown target (adjust to your launch date/time)
  const target = new Date();
  target.setDate(target.getDate() + 14); // default: 14 days from now
  target.setHours(12,0,0,0);

  function updateCountdown(){
    const now = new Date();
    let diff = Math.max(0, target - now);
    const days = Math.floor(diff / (1000*60*60*24));
    diff -= days * (1000*60*60*24);
    const hours = Math.floor(diff / (1000*60*60));
    diff -= hours * (1000*60*60);
    const minutes = Math.floor(diff / (1000*60));
    diff -= minutes * (1000*60);
    const seconds = Math.floor(diff / 1000);
    document.getElementById('days').textContent = String(days).padStart(2,'0');
    document.getElementById('hours').textContent = String(hours).padStart(2,'0');
    document.getElementById('minutes').textContent = String(minutes).padStart(2,'0');
    document.getElementById('seconds').textContent = String(seconds).padStart(2,'0');
  }
  updateCountdown();
  setInterval(updateCountdown,1000);
</script>
</body>
</html>
