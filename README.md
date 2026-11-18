# vanilson-
<!DOCTYPE html>
<html lang="pt-AO">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Colômbia Sub-17 – ADJILE. Acompanhe a equipa, o plantel, notícias e convocatórias.">
  <meta name="theme-color" content="#080b12">
  <title>Colômbia Sub-17 | ADJILE</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;600;700;800;900&family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">
  <link rel="stylesheet" href="styles/style.css">
  <style>
  *{margin:0;padding:0;box-sizing:border-box}
:root{--black:#080b12;--dark:#101622;--red:#f01825;--yellow:#ffc928;--blue:#1453a6;--white:#fff;--muted:#aab1bd}
html{scroll-behavior:smooth;scroll-padding-top:82px}
body{font-family:Inter,Arial,sans-serif;background:#fff;color:var(--black);line-height:1.6}
a{text-decoration:none;color:inherit}.container{width:min(1160px,90%);margin:auto}
.site-header{height:78px;background:#080b12;color:#fff;position:sticky;top:0;z-index:1000;border-bottom:1px solid #ffffff18}
.nav{height:100%;display:flex;align-items:center;justify-content:space-between}
.brand,.footer-brand{display:flex;align-items:center;gap:10px;font-family:'Barlow Condensed',sans-serif;font-size:21px;font-weight:900;letter-spacing:1px}
.brand img{width:48px;height:48px;object-fit:contain}.brand b,.footer-brand b{color:var(--yellow)}
.nav-links{display:flex;align-items:center;gap:30px;font-size:12px;font-weight:800;letter-spacing:1px;text-transform:uppercase}
.nav-links a{transition:.2s}.nav-links a:hover{color:var(--yellow)}
.nav-links .nav-cta{padding:11px 18px;background:var(--red);border-radius:3px}
.menu-toggle{display:none;background:none;border:0;color:#fff;font-size:30px}
.hero{min-height:660px;background:linear-gradient(110deg,#080b12 0%,#111827 60%,#07101e 100%);color:#fff;position:relative;overflow:hidden;display:flex;align-items:center}
.hero:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 85% 50%,#1453a644,transparent 38%),radial-gradient(circle at 0% 100%,#f0182533,transparent 36%)}
.hero-overlay{position:absolute;inset:0;background:linear-gradient(90deg,#080b12 5%,#080b12e8 48%,transparent 100%)}
.hero-content{position:relative;z-index:2;padding:100px 0 125px}
.eyebrow{font-size:11px;font-weight:800;letter-spacing:2.4px;color:var(--yellow);display:flex;align-items:center;gap:10px;margin-bottom:18px}
.eyebrow span{display:inline-block;width:27px;height:3px;background:var(--red)}
.hero h1,.section h2,.banner h2,.contact-section h2{font-family:'Barlow Condensed',sans-serif;font-size:clamp(48px,7vw,82px);line-height:.96;font-weight:900;letter-spacing:1px}
h1 em,h2 em{font-style:normal;color:var(--yellow)}
.hero-text{max-width:490px;color:#c4cad4;margin:25px 0 30px;font-size:15px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-flex;align-items:center;gap:12px;padding:14px 21px;font-size:11px;font-weight:900;letter-spacing:1px;border:1px solid transparent;transition:.2s}
.btn-primary{background:var(--red);color:#fff}.btn-primary:hover{background:#c90d19;transform:translateY(-2px)}
.btn-outline{border-color:#ffffff66;color:#fff}.btn-outline:hover{border-color:var(--yellow);color:var(--yellow)}
.hero-crest{position:absolute;right:max(7%,calc((100% - 1160px)/2));top:50%;transform:translateY(-50%);width:min(36vw,410px);z-index:1;filter:drop-shadow(0 25px 35px #0009)}
.hero-crest img{width:100%;display:block;border-radius:50%}
.hero-tag{display:flex;flex-direction:column;margin-top:65px;border-left:3px solid var(--red);padding-left:13px}
.hero-tag strong{font-family:'Barlow Condensed';font-size:23px;letter-spacing:3px}.hero-tag span{font-size:9px;letter-spacing:2px;color:var(--muted)}
.hero-bottom{position:absolute;bottom:0;left:0;right:0;border-top:1px solid #ffffff25;padding:16px 5%;display:flex;justify-content:space-between;font-size:9px;letter-spacing:2px;color:#aab1bd}
.quick-strip{background:var(--yellow);padding:23px 0}
.strip-inner{display:grid;grid-template-columns:repeat(3,1fr);gap:25px}
.strip-inner div{display:grid;grid-template-columns:35px 1fr;align-items:center;column-gap:10px}
.strip-inner i{grid-row:span 2;font-size:24px}.strip-inner span{font-size:9px;font-weight:900;letter-spacing:1.5px}.strip-inner strong{font-size:12px}
.section{padding:100px 0}.about-grid{display:grid;grid-template-columns: .9fr 1.1fr;gap:85px;align-items:center}
.about-image{position:relative;background:#090d16;padding:25px;min-height:400px;display:flex;align-items:center;justify-content:center;overflow:hidden}
.about-image:before{content:"";position:absolute;width:280px;height:280px;border:1px solid #ffffff20;border-radius:50%}
.about-image img{width:min(82%,330px);position:relative;z-index:1;border-radius:50%}
.image-caption{position:absolute;bottom:0;left:0;right:0;background:var(--red);color:#fff;padding:11px 18px;display:flex;justify-content:space-between;font-size:10px;letter-spacing:2px;font-weight:800}
.image-caption b{color:var(--yellow)}
.eyebrow.dark{color:#555e6c}.about-copy h2,.gallery-section h2{font-size:clamp(42px,5vw,62px);margin-bottom:22px}.about-copy h2 em,.gallery-section h2 em{color:var(--red)}
.about-copy>p:not(.eyebrow){color:#626b78;font-size:14px;margin:0 0 15px;max-width:590px}
.coach-card{display:flex;align-items:center;gap:15px;margin-top:30px;padding:17px;background:#f2f4f7;border-left:4px solid var(--red);max-width:290px}
.coach-icon{width:48px;height:48px;background:#101622;color:var(--yellow);display:grid;place-items:center;font-size:23px}
.coach-card div:last-child{display:flex;flex-direction:column}.coach-card small{font-size:8px;letter-spacing:1.5px;color:#7b8491;font-weight:800}.coach-card strong{font-family:'Barlow Condensed';font-size:23px;line-height:1.2}.coach-card span{font-size:11px;color:#68717d}
.squad-section{background:#0b101a;color:#fff}.section-heading{display:flex;justify-content:space-between;align-items:end;margin-bottom:42px;gap:20px}
.section-heading h2{font-size:58px}.section-heading h2 em{color:var(--yellow)}
.section-heading>p{font-size:12px;color:#aab1bd;text-align:right}
.squad-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:13px}
.player-card{min-height:135px;background:#151d2a;border:1px solid #ffffff12;padding:17px;position:relative;display:flex;flex-direction:column;justify-content:end;overflow:hidden;transition:.2s}
.player-card:before{content:"";position:absolute;top:-35px;right:-25px;width:95px;height:95px;border:12px solid #ffffff08;border-radius:50%}
.player-card:hover{transform:translateY(-4px);border-color:var(--red);background:#1b2535}
.player-card>span{position:absolute;top:12px;left:16px;font-family:'Barlow Condensed';font-size:25px;color:var(--red);font-weight:900}
.player-card strong{font-family:'Barlow Condensed';font-size:24px;text-transform:uppercase;letter-spacing:.5px}
.player-card small{font-size:8px;letter-spacing:2px;color:#8993a2;font-weight:800}
.roster-note{margin-top:20px;color:#8993a2;font-size:10px}.roster-note i{color:var(--yellow);margin-right:5px}
.banner{background:var(--red);color:#fff;padding:55px 0;overflow:hidden;position:relative}
.banner-inner{display:flex;align-items:center;gap:35px}.banner img{width:140px;border-radius:50%;border:4px solid #ffffff35}
.banner .eyebrow{color:#fff}.banner h2{font-size:clamp(38px,5vw,60px)}.banner h2 em{color:var(--yellow)}
.gallery-section .section-heading h2{font-size:54px}
.gallery-grid{display:grid;grid-template-columns:1.3fr 1fr 1fr;gap:14px}
.gallery-main,.gallery-placeholder{min-height:230px;position:relative;overflow:hidden;background:#0b101a;color:#fff;display:flex;align-items:center;justify-content:center;flex-direction:column}
.gallery-main img{width:170px;border-radius:50%}.gallery-main span{position:absolute;bottom:14px;left:16px;font-size:10px;font-weight:900;letter-spacing:2px}
.gallery-placeholder{background:linear-gradient(145deg,#19263a,#0b101a);gap:7px}
.gallery-placeholder.red{background:linear-gradient(145deg,#f01825,#8c0c18)}
.gallery-placeholder i{font-size:35px;color:var(--yellow)}.gallery-placeholder strong{font-family:'Barlow Condensed';font-size:23px}.gallery-placeholder small{font-size:8px;letter-spacing:1.5px;color:#ffffffa8}
.contact-section{background:#111927;color:#fff;padding:65px 0}
.contact-inner{display:flex;justify-content:space-between;align-items:center;gap:25px}.contact-section h2{font-size:clamp(40px,5vw,60px)}.contact-section h2 em{color:var(--yellow)}
.footer{background:#070a10;color:#aab1bd;padding:20px 0}
.footer-inner{display:flex;align-items:center;justify-content:space-between;gap:20px}
.footer-brand{color:#fff;font-size:17px}.footer-brand img{width:40px;height:40px;object-fit:contain}
.footer p{font-size:8px;letter-spacing:1px;text-align:center}.back-top{width:35px;height:35px;border:1px solid #ffffff35;display:grid;place-items:center;color:#fff}
@media(max-width:850px){.hero-crest{right:2%;width:34vw;opacity:.8}.about-grid{gap:35px}.squad-grid{grid-template-columns:repeat(3,1fr)}}
@media(max-width:650px){.site-header{height:68px}.brand{font-size:18px}.brand img{width:42px;height:42px}.menu-toggle{display:block}.nav-links{display:none;position:absolute;top:68px;left:0;right:0;background:#080b12;padding:20px 5% 25px;flex-direction:column;align-items:stretch;gap:0;border-top:1px solid #ffffff20}.nav-links.show{display:flex}.nav-links a{padding:13px 0}.nav-links .nav-cta{text-align:center;margin-top:8px;padding:12px}
.hero{min-height:640px}.hero-content{padding:95px 0 120px}.hero h1{font-size:58px}.hero-crest{width:220px;right:-35px;top:20%;transform:none;opacity:.28}.hero-overlay{background:linear-gradient(90deg,#080b12 0%,#080b12df 75%,#080b12a0 100%)}
.hero-text{font-size:13px;max-width:360px}.hero-tag{margin-top:45px}
.strip-inner{grid-template-columns:1fr;gap:16px}.strip-inner div{grid-template-columns:30px 1fr}.strip-inner i{font-size:20px}
.section{padding:70px 0}.about-grid{grid-template-columns:1fr;gap:35px}.about-image{min-height:300px}.about-image img{width:230px}
.section-heading{align-items:start;flex-direction:column}.section-heading h2{font-size:48px}.section-heading>p{text-align:left}
.squad-grid{grid-template-columns:repeat(2,1fr);gap:9px}.player-card{min-height:115px;padding:13px}.player-card strong{font-size:21px}
.banner-inner{gap:18px}.banner img{width:95px}.banner h2{font-size:36px}.banner .eyebrow{font-size:8px;letter-spacing:1px}
.gallery-grid{grid-template-columns:1fr 1fr}.gallery-main{grid-column:span 2;min-height:220px}.gallery-placeholder{min-height:170px}.gallery-section .section-heading h2{font-size:43px}
.contact-inner{align-items:flex-start;flex-direction:column}.contact-section{padding:55px 0}
.footer-inner{flex-wrap:wrap}.footer p{order:3;width:100%;text-align:left}
}
@media(max-width:360px){.hero h1{font-size:49px}.squad-grid{grid-template-columns:1fr 1fr}.player-card strong{font-size:18px}}

  </style>
</head>
<body>
  <header class="site-header">
    <nav class="nav container">
      <a class="brand" href="#inicio" aria-label="Colômbia Sub-17 início">
        <img src="col.png" alt="Escudo da Colômbia Sub-17">
        <span>COLÔMBIA <b>SUB-17</b></span>
      </a>
      <button class="menu-toggle" id="menuToggle" aria-label="Abrir menu" aria-expanded="false">
        <i class="bi bi-list"></i>
      </button>
      <div class="nav-links" id="navLinks">
        <a href="#inicio">Início</a>
        <a href="#equipa">A equipa</a>
        <a href="#plantel">Plantel</a>
        <a href="#galeria">Galeria</a>
        <a class="nav-cta" href="#contactos">Contactos</a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero" id="inicio">
      <div class="hero-overlay"></div>
      <div class="container hero-content">
        <p class="eyebrow"><span></span> PAIXÃO • UNIÃO • DISCIPLINA</p>
        <h1>O FUTURO<br><em>ENTRA EM CAMPO.</em></h1>
        <p class="hero-text">Uma equipa. Uma família. Um só objetivo: representar as nossas cores com orgulho.</p>
        <div class="hero-actions">
          <a href="#plantel" class="btn btn-primary">CONHECER O PLANTEL <i class="bi bi-arrow-right"></i></a>
          <a href="#equipa" class="btn btn-outline">SOBRE A EQUIPA</a>
        </div>
        <div class="hero-tag"><strong>ADJILE</strong><span>COLÔMBIA SUB-17</span></div>
      </div>
      <div class="hero-crest">
        <img src="assets/escudo-colombia-sub17.png" alt="Escudo oficial Colômbia Sub-17">
      </div>
      <div class="hero-bottom"><span>JUNTOS SOMOS MAIS FORTES</span><span>01 / 04</span></div>
    </section>

    <section class="quick-strip">
      <div class="container strip-inner">
        <div><i class="bi bi-shield-fill"></i><span>IDENTIDADE</span><strong>Orgulho nas nossas cores</strong></div>
        <div><i class="bi bi-people-fill"></i><span>PLANTEL</span><strong>Talento e união</strong></div>
        <div><i class="bi bi-trophy-fill"></i><span>OBJETIVO</span><strong>Dar sempre o nosso melhor</strong></div>
      </div>
    </section>

    <section class="section about-section" id="equipa">
      <div class="container about-grid">
        <div class="about-image">
          <img src="assets/escudo-colombia-sub17.png" alt="Emblema da Colômbia Sub-17">
          <div class="image-caption"><span>O NOSSO EMBLEMA</span><b>ADJILE</b></div>
        </div>
        <div class="about-copy">
          <p class="eyebrow dark"><span></span> QUEM SOMOS</p>
          <h2>MAIS DO QUE UMA EQUIPA.<br><em>UMA FAMÍLIA.</em></h2>
          <p>A Colômbia Sub-17 é feita de jovens que acreditam no trabalho, no respeito e na força do coletivo. Entramos em campo para aprender, evoluir e lutar juntos em cada desafio.</p>
          <p>As nossas cores representam a nossa identidade. O nosso compromisso é honrá-las dentro e fora do campo.</p>
          <div class="coach-card">
            <div class="coach-icon"><i class="bi bi-person-badge-fill"></i></div>
            <div><small>COMANDO TÉCNICO</small><strong>Marcos</strong><span>Treinador</span></div>
          </div>
        </div>
      </div>
    </section>

    <section class="section squad-section" id="plantel">
      <div class="container">
        <div class="section-heading">
          <div><p class="eyebrow"><span></span> OS NOSSOS JOGADORES</p><h2>O <em>PLANTEL</em></h2></div>
          <p>Unidos pelo mesmo símbolo.<br>Preparados para cada desafio.</p>
        </div>
        <div class="squad-grid" id="squadGrid">
          <article class="player-card"><span>01</span><strong>Delcio</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>02</span><strong>Vani</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>03</span><strong>Anderson</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>04</span><strong>Kelson</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>05</span><strong>Ti Noca</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>06</span><strong>Dino</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>07</span><strong>Anjo</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>08</span><strong>Edy</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>09</span><strong>Lyon</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>10</span><strong>Dezaly</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>11</span><strong>Principe</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>11</span><strong>Neston</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>12</span><strong>Gui</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>13</span><strong>Nelo</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>14</span><strong>Baga</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>15</span><strong>Zeca</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>16</span><strong>Beliba</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>17</span><strong>Nandinho</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>18</span><strong>Bele</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>19</span><strong>Tonilson</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>20</span><strong>Mickey</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>21</span><strong>Txoboy</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>22</span><strong>Nancy</strong><small>JOGADOR</small></article>
          <article class="player-card"><span>23</span><strong>Isney</strong><small>JOGADOR</small></article>
        </div>
        <p class="roster-note"><i class="bi bi-info-circle"></i> Numeração apresentada conforme a lista recebida. Pode ser atualizada pela equipa.</p>
      </div>
    </section>

    <section class="banner">
      <div class="container banner-inner">
        <img src="col.png" alt="">
        <div><p class="eyebrow"><span></span> A NOSSA MENTALIDADE</p><h2>RESPEITO PELO JOGO.<br><em>ORGULHO NA CAMISOLA.</em></h2></div>
      </div>
    </section>

    <section class="section gallery-section" id="galeria">
      <div class="container">
        <div class="section-heading">
          <div><p class="eyebrow dark"><span></span> MOMENTOS DA EQUIPA</p><h2> A NOSSA <em>GALERIA</em></h2></div>
          <p>Espaço reservado para fotografias<br>dos jogos, treinos e conquistas.</p>
        </div>
        <div class="gallery-grid">
          <div class="gallery-main"><img src="col.png" alt="Escudo da equipa"><span>O NOSSO SÍMBOLO</span></div>
          <div class="gallery-placeholder"><i class="bi bi-camera-fill"></i><strong>DIAS DE TREINO</strong><small>ADICIONA AS TUAS FOTOGRAFIAS</small></div>
          <div class="gallery-placeholder red"><i class="bi bi-trophy-fill"></i><strong>DIAS DE JOGO</strong><small>ADICIONA AS TUAS FOTOGRAFIAS</small></div>
        </div>
      </div>
    </section>

    <section class="contact-section" id="contactos">
      <div class="container contact-inner">
        <div><p class="eyebrow"><span></span> FAZ PARTE DA NOSSA CAMINHADA</p><h2>UMA SÓ EQUIPA.<br><em>UM SÓ CORAÇÃO.</em></h2></div>
        <a class="btn btn-primary" href="mailto:contacto@colombiasub17.com">ENTRAR EM CONTACTO <i class="bi bi-arrow-right"></i></a>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer-inner">
      <a class="footer-brand" href="#inicio"><img src="col.png" alt=""><span>COLÔMBIA <b>SUB-17</b></span></a>
      <p>© <span id="year"></span> COLÔMBIA SUB-17 – ADJILE. TODOS OS DIREITOS RESERVADOS.</p>
      <a class="back-top" href="#inicio" aria-label="Voltar ao topo"><i class="bi bi-arrow-up"></i></a>
    </div>
  </footer>
  <script src="scripts/script.js"></script>
</body>
</html>
