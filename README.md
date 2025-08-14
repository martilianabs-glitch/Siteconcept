html = """
<!DOCTYPE html>
<html lang=\"fr\">
<head>
  <meta charset=\"utf-8\">
  <meta name=\"viewport\" content=\"width=device-width, initial-scale=1\">
  <title>Concept Car 2000 | Restauration automobile premium en Suisse</title>
  <meta name=\"description\" content=\"Concept Car 2000: restauration automobile premium. Polissage, Lustrage, Cire, PPF (film de protection), Fabrication de pièces en carbone, Restauration cuir et Conciergerie. Excellence depuis 2019.\">
  <meta name=\"keywords\" content=\"restauration automobile de luxe, polissage, lustrage, cire, PPF, film de protection, pièces en carbone, restauration cuir, conciergerie, detailing premium\">
  <link rel=\"canonical\" href=\"https://www.conceptcar2000.com/\">
  <meta property=\"og:title\" content=\"Concept Car 2000 | Restauration automobile premium\">
  <meta property=\"og:description\" content=\"Polissage, Lustrage, Cire, PPF, Carbone, Cuir et Conciergerie pour voitures sportives de luxe.\">
  <meta property=\"og:type\" content=\"website\">
  <meta property=\"og:url\" content=\"https://www.conceptcar2000.com/\">
  <meta property=\"og:image\" content=\"https://images.unsplash.com/photo-1518552718880-5c0829c2fd7d?auto=format&fit=crop&w=1600&q=80\">
  <meta name=\"twitter:card\" content=\"summary_large_image\">
  <meta name=\"twitter:title\" content=\"Concept Car 2000 | Restauration automobile premium\">
  <meta name=\"twitter:description\" content=\"Excellence en restauration pour voitures sportives de luxe.\">
  <meta name=\"twitter:image\" content=\"https://images.unsplash.com/photo-1518552718880-5c0829c2fd7d?auto=format&fit=crop&w=1600&q=80\">

  <link rel=\"preconnect\" href=\"https://fonts.googleapis.com\">
  <link rel=\"preconnect\" href=\"https://fonts.gstatic.com\" crossorigin>
  <link href=\"https://fonts.googleapis.com/css2?family=Montserrat:wght@700;800&family=Lato:wght@300;400;700&family=Orbitron:wght@600;700&display=swap\" rel=\"stylesheet\">
  <link rel=\"stylesheet\" href=\"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css\" crossorigin=\"anonymous\" referrerpolicy=\"no-referrer\">

  <style>
    :root{
      --bg:#0a0a0a; /* fond noir élégant */
      --panel:#121212; /* panneaux */
      --text:#eaeaea; /* texte principal */
      --muted:#bdbdbd; /* texte secondaire */
      --neon:#00d9ff; /* bleu électrique subtil pour icônes/boutons */
      --accent:#ff2d55; /* rouge pour CTA */
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0;background:var(--bg);color:var(--text);font-family:Lato, Arial, sans-serif}

    /* util */
    .container{max-width:1200px;margin:0 auto;padding:0 20px}
    section{padding:80px 0}
    .section-title{font-family:Orbitron, Montserrat, sans-serif;font-weight:700;letter-spacing:.5px;text-align:center;margin:0 0 10px;color:#fff;text-shadow:0 0 10px rgba(0,217,255,.25)}
    .section-sub{color:var(--muted);text-align:center;margin:0 0 40px}
    .btn{display:inline-block;padding:12px 22px;border-radius:10px;text-decoration:none;font-weight:800;letter-spacing:.3px;transition:transform .2s, box-shadow .25s, background .25s}
    .btn-cta{background:var(--accent);color:#fff;box-shadow:0 0 16px rgba(255,45,85,.25)}
    .btn-cta:hover{transform:translateY(-2px);box-shadow:0 0 22px rgba(255,45,85,.45)}
    .icon-neon{color:var(--neon);filter:drop-shadow(0 0 6px rgba(0,217,255,.5))}

    /* Header */
    .header{position:fixed;inset:0 0 auto 0;z-index:1000;background:rgba(10,10,10,.9);backdrop-filter:blur(8px) saturate(140%);border-bottom:1px solid rgba(255,255,255,.06)}
    .nav{display:flex;align-items:center;justify-content:space-between;height:72px}
    .logo{color:#fff;text-decoration:none;font-family:Orbitron, Montserrat, sans-serif;font-weight:700;letter-spacing:2px;font-size:18px;text-shadow:0 0 8px rgba(255,255,255,.2)}
    .menu{display:flex;gap:24px;align-items:center}
    .menu a{color:#eaeaea;text-decoration:none;font-weight:600;transition:color .2s}
    .menu a:hover{color:#fff}
    .burger{display:none;color:#fff;font-size:24px;cursor:pointer}

    /* Hero */
    .hero{min-height:100vh;display:grid;place-items:center;padding-top:72px;position:relative;overflow:hidden}
    .hero-bg{position:absolute;inset:0;background:linear-gradient(180deg, rgba(0,0,0,.55), rgba(0,0,0,.7)), url('https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat}
    .hero-wrap{position:relative;text-align:center;max-width:1100px;padding:0 20px}
    .hero h1{font-family:Montserrat, Orbitron, sans-serif;font-weight:800;font-size:46px;line-height:1.12;margin:0 0 14px;color:#fff;text-shadow:0 0 8px rgba(255,255,255,.25)}
    .hero p{font-size:18px;color:#e8e8e8;opacity:.95;margin:0 0 24px}

    /* Services */
    .services-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:26px}
    .card{background:linear-gradient(180deg, #141414, #0f0f0f);border:1px solid rgba(255,255,255,.06);border-radius:16px;overflow:hidden;box-shadow:0 10px 30px rgba(0,0,0,.35)}
    .card-media{height:200px;background:#000;overflow:hidden}
    .card-media img{width:100%;height:100%;object-fit:cover;filter:saturate(110%)}
    .card-body{padding:18px}
    .card-title{display:flex;align-items:center;gap:10px;font-family:Montserrat, sans-serif;font-weight:800}
    .card-text{color:var(--muted)}

    /* Compare Gallery */
    .compare-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .compare{position:relative;border-radius:14px;overflow:hidden;border:1px solid rgba(255,255,255,.08);box-shadow:0 8px 24px rgba(0,0,0,.35)}
    .compare .img-wrap{position:relative}
    .compare img{display:block;width:100%;height:340px;object-fit:cover}
    .compare .after{position:absolute;inset:0;overflow:hidden;width:50%}
    .compare .after img{width:100%;height:100%;object-fit:cover}
    .slider{position:absolute;left:0;bottom:14px;width:100%;background:transparent}
    .slider input{width:100%;appearance:none;background:transparent}
    .slider input::-webkit-slider-runnable-track{height:3px;background:rgba(0,217,255,.6);border-radius:3px;box-shadow:0 0 8px rgba(0,217,255,.35)}
    .slider input::-webkit-slider-thumb{appearance:none;margin-top:-7px;width:18px;height:18px;border-radius:50%;background:var(--accent);border:2px solid #fff;box-shadow:0 0 10px rgba(255,45,85,.6)}
    .slider input::-moz-range-track{height:3px;background:rgba(0,217,255,.6)}
    .slider input::-moz-range-thumb{width:18px;height:18px;border-radius:50%;background:var(--accent);border:2px solid #fff;box-shadow:0 0 10px rgba(255,45,85,.6)}

    /* About */
    .about{display:grid;grid-template-columns:1.1fr .9fr;gap:26px;align-items:center}
    .about img{width:100%;height:100%;object-fit:cover;border-radius:16px;border:1px solid rgba(255,255,255,.08);box-shadow:0 12px 36px rgba(0,0,0,.4)}
    .about h3{font-family:Montserrat, sans-serif;font-weight:800;margin:0 0 10px}
    .badges{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px}
    .badge{background:#141414;color:#e6e6e6;border:1px solid rgba(255,255,255,.08);padding:8px 12px;border-radius:999px}

    /* Testimonials */
    .testimonials{background:linear-gradient(180deg, #0a0a0a, #0e0e0e)}
    .testi-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .testi{background:#141414;border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,.35)}
    .client{display:flex;align-items:center;gap:12px;margin-bottom:10px}
    .client img{width:46px;height:46px;border-radius:50%;object-fit:cover;border:2px solid rgba(0,217,255,.6)}
    .client strong{font-weight:800}
    .client small{color:var(--muted)}

    /* Contact */
    .contact{display:grid;grid-template-columns:1fr 1fr;gap:24px}
    .contact-card{background:#141414;border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,.35)}
    form .row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    form input, form textarea{width:100%;padding:12px 14px;border-radius:10px;border:1px solid rgba(255,255,255,.14);background:#0f0f0f;color:#eaeaea;outline:none}
    form textarea{min-height:120px;resize:vertical}

    /* Footer */
    footer{border-top:1px solid rgba(255,255,255,.08);background:#080808;color:#d6d6d6}
    .footer-grid{display:grid;grid-template-columns:2fr 1fr 1fr;gap:20px;align-items:start}
    .footer-grid a{color:#ddd;text-decoration:none}
    .social a{margin-right:12px}
    .map{border:0;width:100%;height:220px;border-radius:12px;filter:invert(90%) hue-rotate(180deg) saturate(.6) brightness(.8)}

    /* Responsive */
    @media (max-width:1000px){
      .services-grid{grid-template-columns:1fr 1fr}
      .compare-grid{grid-template-columns:1fr 1fr}
      .about{grid-template-columns:1fr}
      .contact{grid-template-columns:1fr}
      .footer-grid{grid-template-columns:1fr 1fr}
    }
    @media (max-width:760px){
      .menu{display:none}
      .burger{display:block}
      .hero h1{font-size:32px}
      .services-grid,.compare-grid,.testi-grid{grid-template-columns:1fr}
      .footer-grid{grid-template-columns:1fr}
      section{padding:64px 0}
    }

    /* reveal on scroll */
    .reveal{opacity:0;transform:translateY(16px);transition:opacity .6s ease, transform .6s ease}
    .reveal.show{opacity:1;transform:none}
  </style>

  <script type=\"application/ld+json\">{
    \"@context\": \"https://schema.org\",
    \"@type\": \"AutoBodyShop\",
    \"name\": \"Concept Car 2000\",
    \"image\": [\"https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&w=1600&q=80\"],
    \"address\": {\"@type\": \"PostalAddress\",\"streetAddress\": \"Rämismatte 5\",\"addressLocality\": \"Ins\",\"addressRegion\": \"BE\",\"postalCode\": \"3232\",\"addressCountry\": \"CH\"},
    \"openingHours\": [\"Mo-Fr 09:00-18:00\", \"Sa 09:00-13:00\"],
    \"telephone\": \"+41-00-000-00-00\",
    \"url\": \"https://www.conceptcar2000.com/\",
    \"sameAs\": [\"https://www.instagram.com/conceptcar2000\",\"https://www.facebook.com/conceptcar2000\"],
    \"priceRange\": \"$$$\"
  }</script>
</head>
<body>
  <!-- Header -->
  <header class=\"header\">
    <div class=\"container nav\">
      <a href=\"#accueil\" class=\"logo\" aria-label=\"Concept Car 2000\">CONCEPT CAR 2000</a>
      <div class=\"burger\" id=\"burger\" aria-label=\"Menu mobile\" aria-expanded=\"false\"><i class=\"fas fa-bars\"></i></div>
      <nav class=\"menu\" id=\"menu\">
        <a href=\"#accueil\">Accueil</a>
        <a href=\"#services\">Services</a>
        <a href=\"#galerie\">Galerie</a>
        <a href=\"#apropos\">À propos</a>
        <a href=\"#temoignages\">Témoignages</a>
        <a href=\"#contact\">Contact</a>
        <a href=\"#contact\" class=\"btn btn-cta\"><i class=\"fa fa-paper-plane icon-neon\"></i> Demander un devis</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id=\"accueil\" class=\"hero\">
    <div class=\"hero-bg\"></div>
    <div class=\"hero-wrap\">
      <h1 class=\"reveal\">Restauração Automotiva com assinatura Concept Car 2000</h1>
      <p class=\"reveal\" style=\"transition-delay:.08s\">Excellence en polissage, lustrage, cire, PPF et restauration haut de gamme depuis 2019.</p>
      <a href=\"#contact\" class=\"btn btn-cta reveal\" style=\"transition-delay:.16s\"><i class=\"fa fa-calendar-check icon-neon\"></i> Demander un devis</a>
    </div>
  </section>

  <!-- Services -->
  <section id=\"services\">
    <div class=\"container\">
      <h2 class=\"section-title\">Services</h2>
      <p class=\"section-sub\">Des prestations conçues pour sublimer et protéger votre sportive de luxe</p>
      <div class=\"services-grid\">
        <!-- Polissage -->
        <article class=\"card reveal\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1571601035754-5c927f2d7edc?auto=format&fit=crop&w=1200&q=80\" alt=\"Polissage professionnel sur supercar\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-sparkles icon-neon\"></i> Polissage</h3>
            <p class=\"card-text\">Correction multi-étapes pour éliminer micro-rayures et hologrammes, révélant une finition miroir.</p>
          </div>
        </article>
        <!-- Lustrage -->
        <article class=\"card reveal\" style=\"transition-delay:.04s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1558981612-27f3b5d91834?auto=format&fit=crop&w=1200&q=80\" alt=\"Lustrage et brillance profonde\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-gem icon-neon\"></i> Lustrage</h3>
            <p class=\"card-text\">Finition haute brillance avec profondeur et clarté, pour un rendu show-car.</p>
          </div>
        </article>
        <!-- Cire -->
        <article class=\"card reveal\" style=\"transition-delay:.08s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1200&q=80\" alt=\"Application de cire premium sur carrosserie\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-circle-dot icon-neon\"></i> Cire</h3>
            <p class=\"card-text\">Protection hydrophobe et éclat durable grâce à des cires et scellants hautes performances.</p>
          </div>
        </article>
        <!-- PPF -->
        <article class=\"card reveal\" style=\"transition-delay:.12s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1606666401880-9b9a690dd5ad?auto=format&fit=crop&w=1200&q=80\" alt=\"Pose de film de protection PPF sur sportive\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-shield-halved icon-neon\"></i> PPF (film de protection)</h3>
            <p class=\"card-text\">Film transparent auto-cicatrisant contre impacts, gravillons et rayures du quotidien.</p>
          </div>
        </article>
        <!-- Carbone -->
        <article class=\"card reveal\" style=\"transition-delay:.16s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&w=1200&q=80\" alt=\"Pièces en carbone sur voiture de sport\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-gears icon-neon\"></i> Fabrication de pièces en carbone</h3>
            <p class=\"card-text\">Conception sur-mesure de composants en fibre de carbone: légèreté, rigidité et esthétique.</p>
          </div>
        </article>
        <!-- Cuir -->
        <article class=\"card reveal\" style=\"transition-delay:.2s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1200&q=80\" alt=\"Restauration de cuir intérieur sur supercar\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-chair icon-neon\"></i> Restauration cuir</h3>
            <p class=\"card-text\">Réparation, teinture et protection des cuirs: volants, sièges et garnitures.</p>
          </div>
        </article>
        <!-- Conciergerie -->
        <article class=\"card reveal\" style=\"transition-delay:.24s\">
          <div class=\"card-media\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1200&q=80\" alt=\"Service de conciergerie automobile\">
          </div>
          <div class=\"card-body\">
            <h3 class=\"card-title\"><i class=\"fas fa-key icon-neon\"></i> Conciergerie</h3>
            <p class=\"card-text\">Gestion complète: prise en charge, suivi des interventions et livraison selon votre agenda.</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Galerie Avant/Après -->
  <section id=\"galerie\">
    <div class=\"container\">
      <h2 class=\"section-title\">Avant & Après</h2>
      <p class=\"section-sub\">Faites glisser le contrôle pour comparer les résultats réels</p>
      <div class=\"compare-grid\">
        <div class=\"compare reveal\">
          <div class=\"img-wrap\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1542362567-6e46e5a4bd03?auto=format&fit=crop&w=1200&q=80\" alt=\"Avant restauration carrosserie\">
            <div class=\"after\" style=\"width:50%\">
              <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1623213079667-f9907aaa7d85?auto=format&fit=crop&w=1200&q=80\" alt=\"Après restauration carrosserie\">
            </div>
          </div>
          <div class=\"slider\"><input type=\"range\" min=\"0\" max=\"100\" value=\"50\" aria-label=\"Comparateur 1\"></div>
        </div>
        <div class=\"compare reveal\" style=\"transition-delay:.06s\">
          <div class=\"img-wrap\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1200&q=80\" alt=\"Avant polissage\">
            <div class=\"after\" style=\"width:50%\">
              <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1549924231-f129b911e442?auto=format&fit=crop&w=1200&q=80\" alt=\"Après polissage\">
            </div>
          </div>
          <div class=\"slider\"><input type=\"range\" min=\"0\" max=\"100\" value=\"50\" aria-label=\"Comparateur 2\"></div>
        </div>
        <div class=\"compare reveal\" style=\"transition-delay:.12s\">
          <div class=\"img-wrap\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1200&q=80\" alt=\"Avant detailing\">
            <div class=\"after\" style=\"width:50%\">
              <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1200&q=80\" alt=\"Après detailing\">
            </div>
          </div>
          <div class=\"slider\"><input type=\"range\" min=\"0\" max=\"100\" value=\"50\" aria-label=\"Comparateur 3\"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- À propos -->
  <section id=\"apropos\">
    <div class=\"container\">
      <h2 class=\"section-title\">À propos de Concept Car 2000</h2>
      <p class=\"section-sub\">Passion, technologie et souci du détail au service de votre automobile</p>
      <div class=\"about\">
        <!-- Remplacez OWNER_IMAGE_URL par la photo du propriétaire fournie -->
        <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1519641471654-76ce0107ad1b?auto=format&fit=crop&w=1200&q=80\" alt=\"Propriétaire au volant d'une sportive\">
        <div>
          <h3>Notre signature depuis 2019</h3>
          <p>Fondée par des passionnés, Concept Car 2000 allie méthodes pointues, produits de référence et procédures contrôlées pour des résultats reproductibles et impeccables. Notre équipe maîtrise le polissage de précision, les protections PPF, la fabrication de pièces en carbone et la restauration de cuirs haut de gamme.</p>
          <div class=\"badges\">
            <span class=\"badge\"><i class=\"fa fa-award icon-neon\"></i> Standard Premium</span>
            <span class=\"badge\"><i class=\"fa fa-microscope icon-neon\"></i> Technologie Avancée</span>
            <span class=\"badge\"><i class=\"fa fa-shield icon-neon\"></i> Satisfaction Garantie</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Témoignages -->
  <section id=\"temoignages\" class=\"testimonials\">
    <div class=\"container\">
      <h2 class=\"section-title\">Témoignages</h2>
      <p class=\"section-sub\">La confiance de propriétaires exigeants</p>
      <div class=\"testi-grid\">
        <div class=\"testi reveal\">
          <div class=\"client\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=200&q=60\" alt=\"Client 1\">
            <div><strong>Jean Dupont</strong><br><small>Porsche 911</small></div>
          </div>
          <p>Finition irréprochable et brillance profonde. Service sérieux et ponctuel.</p>
        </div>
        <div class=\"testi reveal\" style=\"transition-delay:.06s\">
          <div class=\"client\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1547425260-76bcadfb4f2c?auto=format&fit=crop&w=200&q=60\" alt=\"Client 2\">
            <div><strong>Marie Bernard</strong><br><small>Ferrari 488</small></div>
          </div>
          <p>Protection durable et rendu spectaculaire. Une équipe à l'écoute.</p>
        </div>
        <div class=\"testi reveal\" style=\"transition-delay:.12s\">
          <div class=\"client\">
            <img loading=\"lazy\" src=\"https://images.unsplash.com/photo-1546539782-6fc531453083?auto=format&fit=crop&w=200&q=60\" alt=\"Client 3\">
            <div><strong>Charles Martin</strong><br><small>Lamborghini Huracán</small></div>
          </div>
          <p>Communication claire et résultat exceptionnel. Je recommande sans réserve.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id=\"contact\">
    <div class=\"container\">
      <h2 class=\"section-title\">Contact</h2>
      <p class=\"section-sub\">Parlez-nous de votre projet et recevez un devis personnalisé</p>
      <div class=\"contact\">
        <div class=\"contact-card\">
          <form action=\"#\" method=\"post\" onsubmit=\"event.preventDefault(); alert('Merci ! Nous vous contacterons très bientôt.');\">
            <div class=\"row\">
              <input type=\"text\" name=\"nom\" placeholder=\"Nom\" required>
              <input type=\"tel\" name=\"telephone\" placeholder=\"Téléphone\" required>
            </div>
            <div class=\"row\">
              <input type=\"email\" name=\"email\" placeholder=\"E-mail\" required>
              <input type=\"text\" name=\"modele\" placeholder=\"Marque/Modèle\" required>
            </div>
            <textarea name=\"message\" placeholder=\"Décrivez le service souhaité (Polissage, Lustrage, Cire, PPF, etc.)\" required></textarea>
            <button class=\"btn btn-cta\" type=\"submit\"><i class=\"fa fa-paper-plane icon-neon\"></i> Demander un devis</button>
          </form>
        </div>
        <div class=\"contact-card\">
          <h3 style=\"margin-top:0; font-family:Montserrat,sans-serif\">Informations</h3>
          <p><i class=\"fa fa-location-dot icon-neon\"></i> Rämismatte 5, 3232 Ins, Suisse</p>
          <p><i class=\"fa fa-envelope icon-neon\"></i> contact@conceptcar2000.com</p>
          <div class=\"social\" style=\"margin:10px 0\">
            <a href=\"#\" aria-label=\"Instagram\"><i class=\"fab fa-instagram icon-neon\"></i></a>
            <a href=\"#\" aria-label=\"Facebook\"><i class=\"fab fa-facebook icon-neon\"></i></a>
          </div>
          <h4 style=\"font-family:Montserrat,sans-serif\">Horaires</h4>
          <ul style=\"padding-left:18px;color:var(--muted)\">
            <li>Lun - Ven: 09:00 - 18:00</li>
            <li>Samedi: 09:00 - 13:00</li>
            <li>Dimanche: Fermé</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class=\"container footer-grid\">
      <div>
        <h3 style=\"margin:0 0 6px;color:#fff;font-family:Orbitron,Montserrat\">Concept Car 2000</h3>
        <p style=\"margin:0 0 10px;color:var(--muted)\">Restauration automobile premium depuis 2019</p>
        <p style=\"margin:0;color:var(--muted)\">Rämismatte 5, 3232 Ins, Suisse</p>
      </div>
      <div>
        <strong style=\"color:#fff\">Contact</strong>
        <p style=\"margin:8px 0;color:var(--muted)\">+41 00 000 00 00</p>
        <p style=\"margin:8px 0;color:var(--muted)\">contact@conceptcar2000.com</p>
        <div class=\"social\" style=\"margin-top:8px\">
          <a href=\"#\" aria-label=\"Instagram\"><i class=\"fab fa-instagram icon-neon\"></i></a>
          <a href=\"#\" aria-label=\"Facebook\"><i class=\"fab fa-facebook icon-neon\"></i></a>
        </div>
      </div>
      <div>
        <strong style=\"color:#fff\">Localisation</strong>
        <iframe class=\"map\" loading=\"lazy\" allowfullscreen=\"\" referrerpolicy=\"no-referrer-when-downgrade\" src=\"https://www.google.com/maps?q=R%C3%A4mismatte%205,%203232%20Ins,%20Suisse&output=embed\"></iframe>
      </div>
    </div>
    <div style=\"text-align:center;margin-top:16px;color:#8a8a8a\">© 2025 Concept Car 2000. Tous droits réservés.</div>
  </footer>

  <script defer>
    // Menu mobile
    const burger = document.getElementById('burger');
    const menu = document.getElementById('menu');
    burger?.addEventListener('click', ()=>{
      const open = getComputedStyle(menu).display !== 'none';
      menu.style.display = open ? 'none' : 'flex';
      menu.style.flexDirection = 'column';
      burger.setAttribute('aria-expanded', String(!open));
    });

    // Sliders comparatifs
    document.querySelectorAll('.compare').forEach(comp=>{
      const range = comp.querySelector('input[type=range]') || comp.querySelector('.slider input');
      const after = comp.querySelector('.after');
      range?.addEventListener('input', e=>{ after.style.width = e.target.value + '%'; });
    });

    // Apparition au scroll
    const observer = new IntersectionObserver(entries=>{
      entries.forEach(en=>{ if(en.isIntersecting){ en.target.classList.add('show'); } });
    }, {threshold:0.12});
    document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));
  </script>
</body>
</html>
"""

with open('/home/user/concept_car_2000_neon_premium_fr.html', 'w', encoding='utf-8') as f:
    f.write(html)

print('/home/user/concept_car_2000_neon_premium_fr.html')
