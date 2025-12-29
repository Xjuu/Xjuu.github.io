
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Webfiy Studio – Nowoczesne strony WWW</title>
<style>
:root{--bg:#0b1020;--card:#11172f;--primary:#6366f1;--secondary:#22d3ee;--accent:#34d399;--text:#e5e7eb;--muted:#94a3b8;--highlight:#6366f1}*{box-sizing:border-box;margin:0;padding:0;font-family:'Inter',Arial,sans-serif}body{background:radial-gradient(circle at top,#111827,var(--bg));color:var(--text);line-height:1.6;overflow-x:hidden;scroll-behavior:smooth}header{padding:20px 40px;display:flex;justify-content:space-between;align-items:center;position:sticky;top:0;backdrop-filter:blur(12px);background:rgba(11,16,32,0.85);z-index:10;flex-wrap:wrap}header strong{font-size:20px}nav{display:flex;align-items:center;position:relative}nav a{color:#ffffff;text-decoration:none;margin-left:20px;font-weight:500;font-size:16px;position:relative;transition:color 0.3s;padding-bottom:4px}nav a.active,nav a:hover{color:#ffffff}nav a.active::after,nav a:hover::after{width:100%}nav a::after{content:'';position:absolute;bottom:0;left:0;width:0;height:3px;background:var(--highlight);border-radius:2px;transition:width 0.3s}.hamburger{display:none;flex-direction:column;cursor:pointer}.hamburger div{width:25px;height:3px;background:var(--text);margin:4px 0;transition:0.4s}@media(max-width:768px){nav{display:none;flex-direction:column;width:100%;margin-top:10px}nav.show{display:flex}.hamburger{display:flex}header a{margin-left:0;margin-top:10px}}.hero{padding:120px 20px;text-align:center;max-width:1000px;margin:auto}.hero h1{font-size:42px;line-height:1.2;margin-bottom:18px;background:linear-gradient(90deg,var(--primary),var(--secondary));-webkit-background-clip:text;-webkit-text-fill-color:transparent}.hero p{font-size:18px;color:var(--muted);margin-bottom:36px}.btn{display:inline-block;padding:14px 32px;border-radius:999px;background:linear-gradient(135deg,var(--primary),var(--secondary));color:#020617;font-weight:700;text-decoration:none;box-shadow:0 25px 50px rgba(99,102,241,0.35);transition:0.4s;cursor:pointer}.btn:hover{transform:translateY(-4px) scale(1.03);box-shadow:0 40px 80px rgba(99,102,241,0.5)}section{padding:100px 20px;max-width:1200px;margin:auto}h2{text-align:center;margin-bottom:50px;font-size:32px}.features,.pricing,.extras{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:30px}.card{background:linear-gradient(180deg,rgba(255,255,255,0.06),rgba(255,255,255,0));border:1px solid rgba(255,255,255,0.1);padding:32px;border-radius:22px;transition:transform 0.8s cubic-bezier(.4,0,.2,1),box-shadow 0.8s cubic-bezier(.4,0,.2,1),opacity 0.8s;opacity:0;transform:translateY(60px) rotateX(15deg)}.card.visible{opacity:1;transform:translateY(0) rotateX(0)}.card:hover{transform:translateY(-10px) scale(1.04);box-shadow:0 50px 100px rgba(0,0,0,0.5)}.card h3{margin-bottom:12px;font-size:20px}.card p,.card li{color:var(--muted);font-size:15px}.badge{display:inline-block;padding:6px 14px;border-radius:999px;background:rgba(99,102,241,0.2);color:var(--secondary);font-size:13px;margin-bottom:14px}.price{font-size:32px;font-weight:900;margin:18px 0;background:linear-gradient(90deg,var(--primary),var(--highlight));-webkit-background-clip:text;-webkit-text-fill-color:transparent}form{display:grid;gap:14px}input,textarea{background:linear-gradient(180deg,rgba(255,255,255,0.06),rgba(255,255,255,0));border:1px solid rgba(255,255,255,0.18);padding:14px 16px;border-radius:14px;color:var(--text);font-size:15px;outline:none;transition:border 0.3s,box-shadow 0.3s}input:focus,textarea:focus{border-color:var(--primary);box-shadow:0 0 0 4px rgba(99,102,241,0.35)}button{padding:14px;border-radius:999px;border:none;background:linear-gradient(135deg,var(--primary),var(--secondary));font-weight:700;cursor:pointer;transition:transform 0.3s,box-shadow 0.3s}button:hover{transform:translateY(-2px) scale(1.02);box-shadow:0 35px 70px rgba(99,102,241,0.5)}.custom-select{position:relative}.select-trigger{background:linear-gradient(180deg,rgba(255,255,255,0.06),rgba(255,255,255,0));border:1px solid rgba(255,255,255,0.18);padding:16px 18px;border-radius:18px;cursor:pointer;display:flex;justify-content:space-between;align-items:center;font-size:16px;transition:border 0.3s,box-shadow 0.3s}.select-trigger::after{content:'▾';transition:transform .3s}.custom-select.open .select-trigger::after{transform:rotate(180deg)}.select-options{position:absolute;top:110%;left:0;right:0;background:rgba(17,23,47,0.98);border:1px solid rgba(255,255,255,0.15);border-radius:18px;overflow:hidden;max-height:0;opacity:0;transform:translateY(-10px) scale(0.97);transition:all 0.4s cubic-bezier(0.4,0,0.2,1);z-index:50;border-top:4px solid var(--highlight)}.custom-select.open .select-options{max-height:320px;opacity:1;transform:translateY(0) scale(1)}.select-options div{padding:18px 20px;cursor:pointer;font-size:16px;transition:background 0.3s}.select-options div:hover{background:rgba(99,102,241,0.25)}@media(max-width:600px){body.select-open{overflow:hidden}.select-options{position:fixed;inset:0;max-height:none;border-radius:0;padding-top:80px;transform:translateY(100%)}.custom-select.open .select-options{transform:translateY(0);opacity:1}.select-options div{font-size:18px;padding:20px 26px}}footer{padding:40px;text-align:center;color:var(--muted);border-top:1px solid rgba(255,255,255,0.1);font-size:15px}
</style>
</head>
<body>
<header>
<strong>Webfiy</strong>
<div class="hamburger" id="hamburger"><div></div><div></div><div></div></div>
<nav id="navMenu">
<a href="#features" class="nav-link">Dlaczego my</a>
<a href="#pricing" class="nav-link">Cennik</a>
<a href="#options" class="nav-link">Opcje</a>
<a href="#contact" class="nav-link">Kontakt</a>
</nav>
</header>
<section class="hero">
<h1>Nowoczesne strony WWW<br>od 300 do 800 zł</h1>
<p>Profesjonalny wygląd, animacje i bezpieczeństwo.</p>
<a class="btn" href="#pricing">Poznaj ofertę</a>
</section>
<section id="features">
<h2>Dlaczego warto</h2>
<div class="features">
<div class="card"><h3>Nowoczesny wygląd</h3><p>Responsywny design dopasowany do wszystkich urządzeń.</p></div>
<div class="card"><h3>Szybkość</h3><p>Optymalizacja pod SEO i wydajność.</p></div>
<div class="card"><h3>Bezpieczeństwo</h3><p>Ochrona formularzy i danych klientów.</p></div>
</div>
</section>
<section id="pricing">
<h2>Cennik (przedziały cenowe)</h2>
<div class="pricing">
<div class="card"><span class="badge">Start</span><h3>Landing Page</h3><p class="price">300–400 zł</p><ul><li>✔ 1 strona (oferta / wizytówka)</li><li>✔ Responsywność (telefon + komputer)</li><li>✔ Formularz kontaktowy</li><li>✔ Podstawowe animacje</li><li>✔ Szybkie wdrożenie</li></ul></div>
<div class="card"><span class="badge">Popularne</span><h3>Strona firmowa</h3><p class="price">450–600 zł</p><ul><li>✔ Do 5 podstron</li><li>✔ Nowoczesny design</li><li>✔ Formularz + wybór tematu</li><li>✔ Animacje przewijania</li><li>✔ Optymalizacja pod SEO</li></ul></div>
<div class="card"><span class="badge">Pro</span><h3>Strona premium</h3><p class="price">6560–800 zł</p><ul><li>✔ Indywidualny projekt</li><li>✔ Rozbudowane animacje</li><li>✔ Lepsze UX i szybkość</li><li>✔ Gotowość pod rozwój</li><li>✔ Wsparcie po wdrożeniu</li></ul></div>
</div>
</section>
<section id="options">
<h2>Opcje dodatkowe</h2>
<div class="pricing">
<div class="card"><h3>Maile pod domeną</h3><p class="price">50–100 zł</p><p>Konfiguracja adresów e-mail (np. kontakt@twojadomena.pl).</p></div>
<div class="card"><h3>Podstawowe SEO</h3><p class="price">100–200 zł</p><p>Optymalizacja strony pod wyszukiwarki i poprawa indeksowania.</p></div>
<div class="card"><h3>Usługa płatności</h3><p class="price">150–250 zł</p><p>Integracja systemu płatności online – można dodać do wizytówki, sklepu lub formularza zamówień.</p></div>
</div>
</section>
<section id="contact">
<h2>Kontakt</h2>
<form action="https://formsubmit.co/drej.webfiy@gmail.com" method="POST">
<input type="hidden" name="_captcha" value="false">
<input type="hidden" name="_subject" id="mailSubject" value="Nowe zapytanie ze strony Webfiy">
<input type="text" name="Imię" placeholder="Imię i nazwisko" required>
<input type="email" name="Email" placeholder="Adres e-mail" required>
<div class="custom-select" id="topicSelect">
<div class="select-trigger">Wybierz temat wiadomości</div>
<div class="select-options">
<div data-value="Wycena strony">Wycena strony</div>
<div data-value="Nowa strona WWW">Nowa strona WWW</div>
<div data-value="Usługi dodatkowe">Usługi dodatkowe</div>
</div>
<input type="hidden" name="Temat" required>
</div>
<textarea name="Wiadomość" rows="5" placeholder="Opisz projekt" required></textarea>
<button type="submit">Wyślij zapytanie</button>
</form>
</section>
<footer>© 2025 Webfiy Studio</footer>
<script>
document.addEventListener('DOMContentLoaded', function(){
  const cards=document.querySelectorAll('.card');
  const observer=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('visible');}})},{threshold:0.15});
  cards.forEach(c=>observer.observe(c));

  const hamburger=document.getElementById('hamburger');
  const navMenu=document.getElementById('navMenu');
  hamburger?.addEventListener('click',()=>navMenu.classList.toggle('show'));

  const navLinks=document.querySelectorAll('nav a');
  const sections=document.querySelectorAll('section');
  window.addEventListener('scroll',()=>{
    let current='';
    sections.forEach(section=>{const sectionTop=section.offsetTop-80;if(pageYOffset>=sectionTop){current=section.getAttribute('id');}});
    navLinks.forEach(link=>link.classList.remove('active'));
    document.querySelector(`nav a[href*='${current}']`)?.classList.add('active');
  });

  const customSelect=document.getElementById('topicSelect');
  const mailSubject=document.getElementById('mailSubject');
  if(customSelect&&mailSubject){
    const trigger=customSelect.querySelector('.select-trigger');
    const options=customSelect.querySelectorAll('.select-options div');
    const hiddenInput=customSelect.querySelector('input[type="hidden"]');

    trigger.addEventListener('click',e=>{
      e.stopPropagation();
      customSelect.classList.toggle('open');
      document.body.classList.toggle('select-open', customSelect.classList.contains('open'));
    });

    options.forEach(opt=>{
      opt.addEventListener('click', e=>{
        e.stopPropagation();
        trigger.textContent=opt.textContent;
        hiddenInput.value=opt.dataset.value;
        mailSubject.value='Webfiy – '+opt.dataset.value;
        customSelect.classList.remove('open');
        document.body.classList.remove('select-open');
      });
    });

    document.addEventListener('click',()=>{
      customSelect.classList.remove('open');
      document.body.classList.remove('select-open');
    });
  }
});
</script>
</body>
</html>
