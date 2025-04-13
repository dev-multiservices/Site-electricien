# Site-electricien
<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Électricien Pro - Accueil</title>
  <style>
    * { box-sizing: border-box; }
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #003366; color: white; padding: 20px; text-align: center; }
    nav { margin-top: 10px; }
    nav a { margin: 0 10px; color: white; text-decoration: none; display: inline-block; padding: 5px; }
    section { padding: 40px 20px; }
    .services, .contact-form { max-width: 800px; margin: auto; }
    .service { margin-bottom: 20px; }
    footer { background: #003366; color: white; text-align: center; padding: 15px; }
    input, textarea { width: 100%; padding: 10px; margin-top: 5px; margin-bottom: 15px; border: 1px solid #ccc; border-radius: 4px; }
    button { background: #0066cc; color: white; padding: 10px 20px; border: none; cursor: pointer; border-radius: 4px; }
    .logo { width: 100px; height: auto; display: block; margin: 0 auto 10px; }@media (max-width: 600px) {
  header, nav, section, footer { padding: 15px; }
  nav a { display: block; margin: 5px 0; }
}

  </style>
</head>
<body>
  <header>
    <img src="IMG_20240713_010119.jpg" alt="Logo Électricien" class="logo">
    <h1>Électricien Pro</h1>
    <nav>
      <a href="#a-propos">À propos</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section id="a-propos">
    <h2>À propos</h2>
    <p>Artisan électricien avec plus de 10 ans d'expérience. Interventions rapides et professionnelles pour tous vos besoins en électricité.</p>
  </section>  <section id="services" class="services">
    <h2>Nos Services</h2>
    <div class="service">
      <h3>Dépannages urgents</h3>
      <p>Intervention rapide 7j/7 en cas de panne électrique.</p>
    </div>
    <div class="service">
      <h3>Installations neuves & rénovations</h3>
      <p>Mise aux normes, installations complètes dans logements ou locaux professionnels.</p>
    </div>
    <div class="service">
      <h3>Domotique & bornes de recharge</h3>
      <p>Automatisez votre maison et installez une borne pour votre véhicule électrique.</p>
    </div>
  </section>  <section id="contact" class="contact-form">
    <h2>Contactez-nous</h2>
    <form>
      <label for="nom">Nom</label>
      <input type="text" id="nom" name="nom" required><label for="email">Email</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">Envoyer</button>
</form>

  </section>  <footer>
    <p>&copy; 2025 Électricien Pro - Tous droits réservés.</p>
  </footer>
</body>
</html>
