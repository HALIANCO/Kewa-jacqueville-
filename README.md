<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kewa Jacqueville</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #1a73e8;
      color: white;
      padding: 1em 2em;
      text-align: center;
      position: relative;
    }
    header img.logo {
      height: 60px;
      position: absolute;
      top: 10px;
      left: 20px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2em;
      max-width: 900px;
      margin: auto;
      background: white;
      margin-top: 2em;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 1em;
      background: #1a73e8;
      color: white;
      margin-top: 2em;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      padding: 10px 20px;
      background-color: #1a73e8;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    img.hero {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 20px;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 8px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 15px;
    }
    .gallery img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .gallery div {
      text-align: center;
    }
    .gallery h4 {
      margin: 10px 0 5px;
    }
    .gallery p {
      margin: 0 0 10px;
    }
    .gallery button {
      padding: 8px 15px;
      background: #1a73e8;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      padding: 15px;
      font-size: 24px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  <img src="https://i.imgur.com/jxWqIBf.png" alt="Logo Kewa" class="logo">
  <h1>Kewa Jacqueville</h1>
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#galerie">Galerie</a>
    <a href="#catalogue">Catalogue</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="accueil">
  <img src="https://source.unsplash.com/900x300/?ivory-coast,beach" alt="Jacqueville" class="hero">
  <h2>Bienvenue à Kewa Jacqueville</h2>
  <p>Kewa est un centre de vente et de distribution situé à Jacqueville, Côte d'Ivoire. Nous fournissons des services fiables pour les habitants et visiteurs.</p>
</section>

<section id="apropos">
  <h2>À propos de nous</h2>
  <p>Notre objectif est de proposer des produits de qualité, accessibles à tous. Nous sommes engagés à soutenir le développement local à travers un service de proximité.</p>
</section>

<section id="galerie">
  <h2>Galerie</h2>
  <div class="gallery">
    <img src="https://source.unsplash.com/400x300/?market,cote-d'ivoire" alt="Image 1">
    <img src="https://source.unsplash.com/400x300/?shop,jacqueville" alt="Image 2">
    <img src="https://source.unsplash.com/400x300/?pharmacy,africa" alt="Image 3">
    <img src="https://source.unsplash.com/400x300/?african-store" alt="Image 4">
  </div>
</section>

<section id="video">
  <h2>Vidéo de Présentation</h2>
  <iframe width="100%" height="315" 
    src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
    title="Présentation de Kewa Jacqueville"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</section>

<section id="brochure">
  <h2>Brochure & Tarifs</h2>
  <p>Téléchargez notre brochure ou la liste de prix en cliquant ci-dessous :</p>
  <a href="brochure-kewa.pdf" download style="background:#1a73e8;color:white;padding:10px 20px;border-radius:5px;text-decoration:none;">📄 Télécharger la brochure</a>
</section>

<section id="catalogue">
  <h2>Notre Catalogue</h2>
  <div class="gallery">
    <div>
      <img src="https://source.unsplash.com/400x300/?label,roll" alt="Rouleaux d'étiquettes">
      <h4>Étiquettes pour Pharmacie</h4>
      <p>Prix : 5 000 FCFA</p>
      <button onclick="alert('Appelez-nous au 0700000000 pour commander')">Commander</button>
    </div>
    <div>
      <img src="https://source.unsplash.com/400x300/?money-counter" alt="Machine à compter">
      <h4>Machine à compter les billets</h4>
      <p>Prix : 55 000 FCFA</p>
      <button onclick="alert('Appelez-nous au 0700000000 pour commander')">Commander</button>
    </div>
    <div>
      <img src="https://source.unsplash.com/400x300/?pharmacy,bags" alt="Sachets pharmacie">
      <h4>Sachets de pharmacie</h4>
      <p>Prix : 2 000 FCFA (par paquet)</p>
      <button onclick="alert('Appelez-nous au 0700000000 pour commander')">Commander</button>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contactez-nous</h2>
  <form action="https://formspree.io/f/mqkrzqoe" method="POST">
    <label>Nom</label>
    <input type="text" name="nom" required>
    
    <label>Email</label>
    <input type="email" name="email" required>
    
    <label>Message</label>
    <textarea name="message" rows="5" required></textarea>
    
    <button type="submit">Envoyer</button>
  </form>
</section>

<section>
  <h2>Nous trouver</h2>
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3978.663320265338!2d-4.416978424074883!3d5.209658837412436!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xfc1ed74ff1d1a9f%3A0x49b601f8e4d22bcb!2sJacqueville!5e0!3m2!1sfr!2sci!4v1682028679482!5m2!1sfr!2sci" 
    allowfullscreen=""
    loading="lazy">
  </iframe>
</section>

<footer>
  &copy; 2025 Kewa Jacqueville. Tous droits réservés.
</footer>

<!-- Bouton WhatsApp -->
<a href="https://wa.me/2250700000000" class="whatsapp" target="_blank" title="Discuter sur WhatsApp">💬</a>

</body>
</html># Kewa-jacqueville-
