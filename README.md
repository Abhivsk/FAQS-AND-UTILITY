<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Samyak Creation Pvt Ltd — Official</title>
  <meta name="description" content="Official site for Samyak Creation Pvt Ltd — best textile manufacturer with news, FAQs, and customizable holiday calendar (owner editable)." />
  <style>
    :root{
      --brand:#004aad;
      --accent:#f8b400;
      --muted:#6b7280;
      --bg:#f4f7fb;
      --white:#ffffff;
      --gold:#d4af37;
    }
    *{box-sizing:border-box;margin:0;padding:0;}
    body{
      font-family:'Poppins',sans-serif;
      background:var(--bg);
      color:#0f1724;
      overflow-x:hidden;
    }
    header{
      background:linear-gradient(90deg,#002244,#0055aa);
      color:var(--white);
      padding:28px 20px;
      position:relative;
      overflow:hidden;
    }
    header::after{
      content:'';
      position:absolute;
      top:-50%;left:-50%;width:200%;height:200%;
      background:radial-gradient(circle at 30% 50%,rgba(255,255,255,0.1),transparent 70%);
      animation:rotateBg 18s linear infinite;
      z-index:0;
    }
    @keyframes rotateBg{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}
    .container{max-width:1100px;margin:18px auto;padding:0 16px;position:relative;z-index:2;}
    .brand{display:flex;align-items:center;gap:12px;}
    .logo{width:60px;height:60px;border-radius:14px;background:var(--white);display:grid;place-items:center;font-weight:800;color:var(--brand);box-shadow:0 4px 10px rgba(0,0,0,0.15);animation:pulse 3s infinite;}
    @keyframes pulse{0%,100%{transform:scale(1);}50%{transform:scale(1.08);}}
    nav{margin-left:auto;display:flex;align-items:center;gap:20px;}
    nav a{color:rgba(255,255,255,0.9);text-decoration:none;position:relative;transition:color .3s;}
    nav a::after{content:'';position:absolute;bottom:-4px;left:0;width:0;height:2px;background:var(--accent);transition:width .3s;}
    nav a:hover{color:#fff;}
    nav a:hover::after{width:100%;}
    #live-time{font-size:14px;margin-left:20px;color:#f8b400;}
    .hero{background:var(--white);border-radius:20px;padding:32px;margin-top:18px;display:flex;gap:30px;align-items:center;box-shadow:0 10px 20px rgba(0,0,0,0.08);animation:fadeIn 1s ease forwards;}
    @keyframes fadeIn{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}
    .hero h1{font-size:26px;margin-bottom:10px;color:var(--brand);}
    .grid{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:20px;}
    .card{background:var(--white);border-radius:14px;padding:20px;box-shadow:0 6px 12px rgba(2,6,23,0.06);transition:transform .3s,box-shadow .3s;}
    .card:hover{transform:translateY(-4px);box-shadow:0 10px 20px rgba(2,6,23,0.1);}
    .small{font-size:13px;color:var(--muted);}
    .news-item{padding:10px;border-radius:10px;border:1px solid #eef2ff;margin-bottom:10px;background:#fafcff;transition:background .3s;}
    .news-item:hover{background:#f0f6ff;}
    .faq q{display:block;padding:10px 0;margin:0;border-bottom:1px dashed #eef2ff;}
    .calendar{display:grid;grid-template-rows:auto auto 1fr;gap:12px;}
    .cal-header{display:flex;justify-content:space-between;align-items:center;}
    .cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:6px;}
    .cal-cell{min-height:72px;padding:8px;border-radius:8px;background:#fff;display:flex;flex-direction:column;transition:background .3s;position:relative;}
    .cal-cell:hover{background:#f8faff;}
    .cal-cell .date{font-weight:600;}
    .holiday{background:linear-gradient(90deg,#fff1e0,#ffe7b8);border:1px solid #ffdca2;padding:6px;border-radius:6px;margin-top:6px;font-size:13px;color:#7a4b00;cursor:pointer;}
    button{background:var(--brand);color:white;border:0;padding:8px 12px;border-radius:8px;cursor:pointer;transition:transform .2s,background .2s;}
    button:hover{transform:translateY(-2px);background:#003a8a;}
    .ghost{background:transparent;color:var(--brand);border:1px solid rgba(11,110,253,0.3);}
    footer{margin:28px 0;text-align:center;color:var(--muted);font-size:14px;}
    @media(max-width:900px){.grid{grid-template-columns:1fr}.hero{flex-direction:column;}}
  </style>
</head>
<body>
  <header>
    <div class="container" style="display:flex;align-items:center;">
      <div class="brand">
        <div class="logo">SC</div>
        <div>
          <div style="font-weight:700;font-size:18px;">Samyak Creation Pvt Ltd</div>
          <div class="small">India’s Leading Textile Manufacturer</div>
        </div>
      </div>
      <div id="live-time"></div>
      <nav>
        <a href="#news">News</a>
        <a href="#faqs">FAQs</a>
        <a href="#calendar">Holiday Calendar</a>
        <a href="#contact">Contact</a>
        <a href="#admin" id="admin-link">Owner</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div style="flex:1">
        <h1>Welcome to Samyak Creation Pvt Ltd</h1>
        <p class="small">We are India’s premier textile manufacturer, delivering high-quality fabrics and innovative designs globally. Explore our updates, FAQs, and customizable holiday calendar.</p>
      </div>
      <div style="width:260px;text-align:right">
        <div class="card" style="background:var(--gold);color:white;">
          <div style="font-weight:700">Office Hours</div>
          <div class="small">Mon — Sat: 9:30 AM — 8:00 PM</div>
          <div style="margin-top:8px" class="small">Support: 9170178772</div>
        </div>
      </div>
    </section>

    <section id="news" style="margin-top:40px;">
      <h2 style="color:var(--brand);margin-bottom:10px;">Utility News</h2>
      <div id="news-list" class="card">
        <div class="news-item">New silk collection launching soon for festive season!</div>
        <div class="news-item">Samyak Creation recognized among top 10 textile exporters 2025.</div>
      </div>
    </section>

    <section id="faqs" style="margin-top:40px;">
      <h2 style="color:var(--brand);margin-bottom:10px;">FAQs</h2>
      <div class="card faq">
        <q>Q: How can I place a bulk order?</q>
        <p>A: Contact our sales team via email or phone for bulk pricing.</p>
        <q>Q: Do you ship internationally?</q>
        <p>A: Yes, we export to over 20 countries.</p>
      </div>
    </section>

    <section id="calendar" style="margin-top:40px;">
      <h2 style="color:var(--brand);margin-bottom:10px;">Holiday Calendar</h2>
      <div class="card calendar">
        <div class="cal-header">
          <h3>November 2025</h3>
          <div>
            <button id="add-holiday">+ Add Holiday</button>
            <button id="remove-holiday" class="ghost">- Remove Holiday</button>
          </div>
        </div>
        <div class="cal-grid" id="cal-grid"></div>
      </div>
    </section>

    <section id="contact" style="margin-top:40px;">
      <h2 style="color:var(--brand);margin-bottom:10px;">Contact Us</h2>
      <div class="card">
        <p>Email: info@samyakcreation.com</p>
        <p>Phone: 9170178772</p>
        <p>Address: VARANASI</p>
      </div>
    </section>
  </main>

  <footer>© Samyak Creation Pvt Ltd — All rights reserved.</footer>

  <script>
    const DEFAULT_ADMIN_PASSWORD = 'samyak-admin';
    let isAdmin = false;

    function updateTime(){
      const now=new Date();
      document.getElementById('live-time').textContent=now.toLocaleTimeString();
    }
    setInterval(updateTime,1000);
    updateTime();

    document.getElementById('admin-link').addEventListener('click',()=>{
      const pass = prompt('Enter Owner Password:');
      if(pass === DEFAULT_ADMIN_PASSWORD){
        alert('Welcome, Owner! You can now edit the holiday calendar.');
        isAdmin = true;
      } else alert('Incorrect password!');
    });

    const calGrid = document.getElementById('cal-grid');
    const holidays = [{date:5,name:'Diwali'},{date:14,name:'Children’s Day'}];

    function renderCalendar(){
      calGrid.innerHTML='';
      for(let d=1;d<=30;d++){
        const cell=document.createElement('div');
        cell.className='cal-cell';
        const dateDiv=document.createElement('div');
        dateDiv.className='date';
        dateDiv.textContent=d;
        cell.appendChild(dateDiv);
        const holiday=holidays.find(h=>h.date===d);
        if(holiday){
          const hDiv=document.createElement('div');
          hDiv.className='holiday';
          hDiv.textContent=holiday.name;
          hDiv.addEventListener('click',()=>{
            if(isAdmin && confirm('Remove this holiday?')){
              const index=holidays.indexOf(holiday);
              holidays.splice(index,1);
              renderCalendar();
            }
          });
          cell.appendChild(hDiv);
        }
        calGrid.appendChild(cell);
      }
    }

    renderCalendar();

    document.getElementById('add-holiday').addEventListener('click',()=>{
      if(!isAdmin) return alert('Only owner can add holidays!');
      const day=parseInt(prompt('Enter date (1-30):'));
      const name=prompt('Enter holiday name:');
      if(!day||!name)return;
      holidays.push({date:day,name:name});
      renderCalendar();
    });

    document.getElementById('remove-holiday').addEventListener('click',()=>{
      if(!isAdmin) return alert('Only owner can remove holidays!');
      const day=parseInt(prompt('Enter date of holiday to remove:'));
      const index=holidays.findIndex(h=>h.date===day);
      if(index>-1){
        holidays.splice(index,1);
        renderCalendar();
      } else alert('No holiday found for that date.');
    });
  </script>
</body>
</html>
