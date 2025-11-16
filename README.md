<!--
  Fayl: kiberxavfsizlik_klubi.html
  Tavsif: Kiberxavfsizlik klubi uchun to'liq bir sahifa (single-page) sayt.
  Muallif/yaratuvchi: Soibnazarov Ro'zimurod
  Kontaktlar: Tel: +998908888963, Telegram: @Soibnazarov07, Email: rozimurodsoyibnazarov2007@gmail.com
  Izoh: Visual Studio yoki VS Code-da ochib, brauzerda oching. Agar Live Server qo'shimchasiga ega bo'lsangiz, sahifani jonli ko'rishingiz mumkin.
-->

<!doctype html>
<html lang="uz">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Kiberxavfsizlik klubi — Soibnazarov Ro'zimurod</title>
  <meta name="description" content="Kiberxavfsizlik klubi. Yangiliklar, o'quv materiallari va aloqa - Soibnazarov Ro'zimurod.">
  <link rel="icon" href="https://images.unsplash.com/photo-1535223289827-42f1e9919769?auto=format&fit=crop&w=64&q=60">
  <style>
    :root{--accent:#0b7285;--dark:#0d1b2a;--muted:#6c757d}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; color:#0f1724; background:linear-gradient(180deg,#f7fbff 0%, #ffffff 100%)}
    header{background:linear-gradient(90deg, rgba(11,114,133,0.95), rgba(3,37,65,0.95)); color:#fff; padding:28px 18px}
    .container{max-width:1100px; margin:0 auto; padding:24px}
    .brand{display:flex; gap:16px; align-items:center}
    .brand img{width:72px; height:72px; border-radius:12px; object-fit:cover; border:2px solid rgba(255,255,255,0.12)}
    .brand h1{font-size:20px; margin:0}
    nav{margin-top:12px}
    nav a{color:rgba(255,255,255,0.95); text-decoration:none; margin-right:14px; font-weight:600}
    .hero{display:grid; grid-template-columns:1fr 360px; gap:24px; align-items:start; margin-top:18px}
    .card{background:#fff; border-radius:12px; padding:18px; box-shadow:0 6px 18px rgba(3,17,30,0.06)}
    .lead{font-size:18px; color:var(--muted)}
    .cta{display:inline-block; background:var(--accent); color:#fff; padding:10px 14px; border-radius:10px; text-decoration:none; margin-top:12px}
    .stats{display:flex; gap:12px; margin-top:12px}
    .stat{flex:1; background:linear-gradient(180deg,#fbffff,#f0f8ff); padding:12px; border-radius:10px; text-align:center}
    .section{margin-top:26px}
    h2{font-size:18px; margin:0 0 12px 0}
    .grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(240px,1fr)); gap:14px}
    .news-item{display:flex; gap:12px}
    .news-item img{width:120px; height:80px; object-fit:cover; border-radius:8px}
    footer{margin-top:28px; padding:18px 0; text-align:center; color:var(--muted); font-size:14px}
    .contact-list{display:flex; flex-direction:column; gap:8px}
    .tag{display:inline-block; padding:6px 10px; border-radius:999px; background:#eef6f8; font-weight:600; color:var(--accent)}
    @media (max-width:880px){ .hero{grid-template-columns:1fr; } }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="brand">
        <img src="https://images.unsplash.com/photo-1535223289827-42f1e9919769?auto=format&fit=crop&w=500&q=60" alt="Kiberxavfsizlik">
        <div>
          <h1>Kiberxavfsizlik klubi — Yaratuvchi: <strong>Soibnazarov Ro'zimurod</strong></h1>
          <div class="lead">Klubimizda xavfsizlik bo'yicha ta'lim, amaliy mashg'ulotlar va yangiliklar mavjud.</div>
        </div>
      </div>
      <nav>
        <a href="#about">Biz haqimizda</a>
        <a href="#materials">Materiallar</a>
        <a href="#news">Yangiliklar</a>
        <a href="#contact">Kontakt</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="card">
        <h2>Xush kelibsiz!</h2>
        <p class="lead">Kiberxavfsizlik klubi talabalar va boshlang'ich mutaxassislar uchun mo'ljallangan. Kurslar, laboratoriyalar, CTF mashg'ulotlari va jamoaviy loyihalar orqali bilimlarni oshiramiz.</p>
        <div class="stats">
          <div class="stat">
            <div style="font-size:20px; font-weight:700">12+</div>
            <div style="font-size:13px; color:var(--muted)">Treninglar</div>
          </div>
          <div class="stat">
            <div style="font-size:20px; font-weight:700">30+</div>
            <div style="font-size:13px; color:var(--muted)">A'zo</div>
          </div>
          <div class="stat">
            <div style="font-size:20px; font-weight:700">5</div>
            <div style="font-size:13px; color:var(--muted)">Loyiha</div>
          </div>
        </div>

        <a class="cta" href="#contact">Qo'shilish / Aloqa</a>

        <div class="section">
          <h2>Tezkor mavzular</h2>
          <ul>
            <li>Penetratsiya testi boshlang'ich qo'llanmasi</li>
            <li>Web xavfsizligi: XSS va SQL Injection</li>
            <li>Kriptografiya asoslari</li>
            <li>Ruxsatlar va autentifikatsiya yaxshilash</li>
          </ul>
        </div>
      </div>

      <aside class="card">
        <h2>Kontakt</h2>
        <div class="contact-list">
          <div><strong>Telefon:</strong> <a href="tel:+998908888963">+998 90 888 89 63</a></div>
          <div><strong>Telegram:</strong> <a href="https://t.me/Soibnazarov07" target="_blank">@Soibnazarov07</a></div>
          <div><strong>Email:</strong> <a href="mailto:rozimurodsoyibnazarov2007@gmail.com">rozimurodsoyibnazarov2007@gmail.com</a></div>
        </div>

        <div style="margin-top:14px">
          <span class="tag">Joriy treninglar</span>
          <p class="lead" style="margin-top:8px">Har haftada amaliy CTF, veb xavfsizlik va tarmoq himoyasi bo'yicha mashg'ulotlar.</p>
        </div>

        <div style="margin-top:12px">
          <img src="https://images.unsplash.com/photo-1556157382-97eda2d62296?auto=format&fit=crop&w=800&q=60" alt="lab" style="width:100%; border-radius:10px; display:block">
        </div>
      </aside>
    </section>

    <section id="about" class="section">
      <div class="card">
        <h2>Biz haqimizda</h2>
        <p>Kiberxavfsizlik klubi — <strong>Soibnazarov Ro'zimurod</strong> tomonidan tashkil etilgan. Maqsadimiz yoshlarni axborot xavfsizligi sohasiga jalb qilish va ularni amaliy ko'nikmalar bilan ta'minlashdir. Klub ichida seminarlar, laboratoriyalar, CTF musobaqalari va loyiha ishlari o'tkaziladi.</p>

        <h3 style="margin-top:14px">Faoliyat yo'nalishlari</h3>
        <ul>
          <li>Tarmoq xavfsizligi</li>
          <li>Veb ilovalar xavfsizligi</li>
          <li>Forensika va hodisa tekshiruvi</li>
          <li>Kriptografiya va autentifikatsiya</li>
        </ul>
      </div>
    </section>

    <section id="materials" class="section">
      <div class="card">
        <h2>O'quv materiallari</h2>
        <div class="grid">
          <div>
            <h4>Penetratsiya testi — boshlang'ich</h4>
            <p class="lead">Penetratsiya testi qanday o'tkaziladi, asosiy vositalar va metodlar (Nmap, Burp Suite, Metasploit) haqida qisqacha.</p>
            <a href="#" class="cta" style="display:inline-block; margin-top:8px">PDF ko'rish</a>
          </div>
          <div>
            <h4>Veb xavfsizligi</h4>
            <p class="lead">XSS, SQL Injection hujumlarini tushunish va ularning oldini olish bo'yicha amaliy misollar.</p>
          </div>
          <div>
            <h4>Kriptografiya asoslari</h4>
            <p class="lead">Simmetrik va asimmetrik shifrlash, hash funksiyalar va ularning qo'llanilishi.</p>
          </div>
          <div>
            <h4>Forensika</h4>
            <p class="lead">Disk forensikasi, hodisa tekshiruvi va yozuvlarni himoya qilish bo'yicha boshlang'ich ko'rsatmalar.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="news" class="section">
      <div class="card">
        <h2>Kiberxavfsizlik yangiliklari</h2>
        <p class="lead">Quyida so'nggi yangiliklardan namunalar (statik misollar). Agar xohlasangiz, sahifani yangilab, avtomatik yangiliklarni olish uchun NewsAPI yoki boshqa manbani ulab berishim mumkin.</p>

        <div class="grid" id="news-grid">
          <!-- Statik namunalar -->
          <div class="card">
            <div class="news-item">
              <img src="https://images.unsplash.com/photo-1555989592-7a9c0f1b2b5b?auto=format&fit=crop&w=800&q=60" alt="news1">
              <div>
                <strong>Yirik tashkilotga ransomware hujumi</strong>
                <div style="font-size:13px; color:var(--muted); margin-top:6px">Tashkilotda muhim ma'lumotlarning shifrlanishi va xizmatlar vaqtincha to'xtatilishi ro'y berdi.</div>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="news-item">
              <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=60" alt="news2">
              <div>
                <strong>Zero-day zaiflik ochildi</strong>
                <div style="font-size:13px; color:var(--muted); margin-top:6px">Mashhur server dasturida nolinchi kun (zero-day) zaiflik aniqlanib, yamalar chiqarildi.</div>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="news-item">
              <img src="https://images.unsplash.com/photo-1526378728456-59e3b7a68b8f?auto=format&fit=crop&w=800&q=60" alt="news3">
              <div>
                <strong>Telekommunikatsiya provayderida ma'lumotlar oqimi</strong>
                <div style="font-size:13px; color:var(--muted); margin-top:6px">Mijozlar ma'lumotlari qat'iy himoyasiz ekani haqida xabarlar paydo bo'ldi.</div>
              </div>
            </div>
          </div>
        </div>

        <!-- JS: agar xohlasangiz, ishlatish uchun NewsAPI kalitini qo'yishingiz mumkin -->
        <script>
          // Agar avtomatik yangiliklarni ulamoqchi bo'lsangiz: NewsAPI yoki boshqa API dan foydalaning.
          // Misol (work only with valid API va server-side yoki CORS ruxsatlari bilan):
          // fetch('https://newsapi.org/v2/everything?q=cybersecurity&language=uz&apiKey=YOUR_NEWSAPI_KEY')
          //   .then(res => res.json())
          //   .then(data => { /* DOM ga yangiliklarni joylash */ })
          //   .catch(err => console.error(err));

          // Interaktiv kichik funksiya: yangiliklarga "bookmark" qo'yish
          document.addEventListener('click', function(e){
            if(e.target && e.target.classList.contains('bookmark')){
              alert('Yangilik saqlandi! (faqat demo)');
            }
          });
        </script>
      </div>
    </section>

    <section id="gallery" class="section">
      <div class="card">
        <h2>Rasmlar galereyasi</h2>
        <div class="grid">
          <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=800&q=60" alt="img1" style="width:100%; height:160px; object-fit:cover; border-radius:8px">
          <img src="https://images.unsplash.com/photo-1510511459019-5dda7724fd87?auto=format&fit=crop&w=800&q=60" alt="img2" style="width:100%; height:160px; object-fit:cover; border-radius:8px">
          <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=800&q=60" alt="img3" style="width:100%; height:160px; object-fit:cover; border-radius:8px">
          <img src="https://images.unsplash.com/photo-1505682634904-d7c45b8e26f3?auto=format&fit=crop&w=800&q=60" alt="img4" style="width:100%; height:160px; object-fit:cover; border-radius:8px">
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="card">
        <h2>Aloqa</h2>
        <p class="lead">Savollaringiz yoki qo'shilish uchun quyidagi shakl orqali murojaat qiling yoki to'g'ridan-to'g'ri bog'laning.</p>

        <form id="contact-form">
          <div style="display:flex; gap:12px; flex-wrap:wrap">
            <input name="name" placeholder="Ismingiz" required style="flex:1; padding:10px; border-radius:8px; border:1px solid #e6eef2">
            <input name="email" placeholder="Email" type="email" required style="flex:1; padding:10px; border-radius:8px; border:1px solid #e6eef2">
          </div>
          <div style="margin-top:8px">
            <input name="phone" placeholder="Telefon (+998...)" value="+998908888963" style="width:100%; padding:10px; border-radius:8px; border:1px solid #e6eef2">
          </div>
          <div style="margin-top:8px">
            <textarea name="message" placeholder="Xabar matni" required style="width:100%; padding:10px; border-radius:8px; border:1px solid #e6eef2" rows="6"></textarea>
          </div>
          <div style="margin-top:8px; display:flex; gap:8px; align-items:center">
            <button type="submit" class="cta">Yuborish</button>
            <small style="color:var(--muted)">Yuborilgan xabar demo rejimda brauzerda saqlanadi.</small>
          </div>
        </form>

        <script>
          document.getElementById('contact-form').addEventListener('submit', function(e){
            e.preventDefault();
            const data = new FormData(e.target);
            const obj = Object.fromEntries(data.entries());
            // Demo rejim: localStorage ga saqlaymiz
            const saved = JSON.parse(localStorage.getItem('kx_club_messages') || '[]');
            saved.push({at: new Date().toISOString(), ...obj});
            localStorage.setItem('kx_club_messages', JSON.stringify(saved));
            alert('Xabaringiz qabul qilindi. Tez orada bog\'lanamiz!');
            e.target.reset();
          });
        </script>

        <div style="margin-top:14px">
          <strong>Tez aloqa:</strong>
          <div style="margin-top:6px"><a href="tel:+998908888963">+998 90 888 89 63</a> • <a href="mailto:rozimurodsoyibnazarov2007@gmail.com">rozimurodsoyibnazarov2007@gmail.com</a> • <a href="https://t.me/Soibnazarov07" target="_blank">Telegram</a></div>
        </div>
      </div>
    </section>

    <footer>
      <div class="container">
        <div>© <strong>Soibnazarov Ro'zimurod</strong> — Kiberxavfsizlik klubi. Barcha huquqlar himoyalangan.</div>
        <div style="margin-top:6px">Manzil: Sizning shahringiz (kerak bo'lsa qo'shib bera olaman)</div>
      </div>
    </footer>
  </main>

</body>
</html>
