<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Studio-Design | Création de logos</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: #111;
      background: #ffffff;
    }
    header {
      background: #0f172a;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 18px;
      opacity: 0.9;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      font-size: 32px;
      margin-bottom: 30px;
      text-align: center;
    }
    .services, .prices {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      border: 1px solid #e5e7eb;
      border-radius: 12px;
      padding: 25px;
      text-align: center;
    }
    .card h3 {
      margin-bottom: 10px;
    }
    .price {
      font-size: 26px;
      font-weight: bold;
      margin: 15px 0;
    }
    .contact {
      text-align: center;
    }
    .contact p {
      font-size: 18px;
    }
    footer {
      background: #f1f5f9;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #555;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 30px;
      background: #0f172a;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>Studio-Design</h1>
    <p>Création de logos professionnels pour entreprises et indépendants</p>
    <a class="btn" href="#contact">Commander un logo</a>
  </header>

  <section>
    <h2>À propos</h2>
    <p style="text-align:center; max-width:700px; margin:auto;">
      Je m'appelle <strong>Jules Jeay</strong>, designer graphique. Je crée tous types de logos : modernes, minimalistes, professionnels ou créatifs, afin d'aider les entreprises à construire une image forte et crédible.
    </p>
  </section>

  <section>
    <h2>Services</h2>
    <div class="services">
      <div class="card">
        <h3>Logo sur mesure</h3>
        <p>Création d'un logo unique et adapté à votre activité.</p>
      </div>
      <div class="card">
        <h3>Refonte de logo</h3>
        <p>Modernisation et amélioration de votre logo existant.</p>
      </div>
      <div class="card">
        <h3>Identité visuelle</h3>
        <p>Logo et supports graphiques cohérents.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Tarifs</h2>
    <div class="prices">
      <div class="card">
        <h3>Logo simple</h3>
        <div class="price">25 – 50 €</div>
        <p>Logo clair et efficace, idéal pour petits projets.</p>
      </div>
      <div class="card">
        <h3>Logo professionnel</h3>
        <div class="price">50 – 100 €</div>
        <p>Logo travaillé avec plusieurs propositions.</p>
      </div>
      <div class="card">
        <h3>Logo + flyers</h3>
        <div class="price">150 €</div>
        <p>Pack complet avec logo et flyers assortis.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Commander / Contact</h2>
    <p>Pour commander un logo ou demander un devis :</p>
    <p><strong>Email :</strong> jeayjules@gmail.com</p>
    <p>Paiement sécurisé via <strong>PayPal</strong></p>

    <a class="btn" href="https://paypal.me/julesjeay" target="_blank">Payer avec PayPal</a>
  </section>

  <footer>
    © Studio-Design – Jules Jeay
  </footer>

</body>
</html>
