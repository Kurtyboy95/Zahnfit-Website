<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ZahnFit – Ihre Zahnzusatzversicherung</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      line-height: 1.6;
      background-color: #f8fbff;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #005bbb, #0077cc);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }

    nav {
      background: #003f7f;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1.5rem;
      padding: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
    }

    .hero {
      background: #e6f3ff;
      text-align: center;
      padding: 4rem 2rem;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .cta {
      background: #005bbb;
      color: white;
      padding: 0.75rem 2rem;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 600;
      margin-top: 1rem;
      display: inline-block;
    }

    section {
      max-width: 960px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    section h2 {
      color: #005bbb;
      margin-bottom: 1rem;
      font-size: 1.75rem;
    }

    ul {
      list-style: none;
      padding-left: 1rem;
    }

    ul li::before {
      content: '✔';
      color: #0077cc;
      font-weight: bold;
      margin-right: 0.5rem;
    }

    footer {
      background: #003f7f;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }

    footer a {
      color: white;
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 1.5rem;
      }

      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>ZahnFit</h1>
    <p>Lächeln ohne Sorgen – mit ZahnFit gut versichert</p>
  </header>

  <nav>
    <a href="#leistungen">Leistungen</a>
    <a href="#warum">Warum wir</a>
    <a href="#rechner">Beitrag</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <section class="hero">
    <h2>Zahnzusatzversicherung, die schützt</h2>
    <p>Top-Leistungen für Zahnersatz, Prophylaxe & mehr.</p>
    <a href="#rechner" class="cta">Jetzt Beitrag berechnen</a>
  </section>

  <section id="leistungen">
    <h2>Unsere Leistungen</h2>
    <ul>
      <li>100 % für professionelle Zahnreinigung</li>
      <li>Bis zu 90 % für Zahnersatz (Implantate, Kronen, Brücken)</li>
      <li>Kieferorthopädie für Kinder & Jugendliche</li>
      <li>Keine Wartezeit bei vielen Tarifen</li>
    </ul>
  </section>

  <section id="warum">
    <h2>Warum ZahnFit?</h2>
    <ul>
      <li>TÜV-geprüfte Qualität</li>
      <li>Persönliche Beratung & digitaler Service</li>
      <li>Monatlich kündbar</li>
    </ul>
  </section>


  <section id="rechner">
  <h2>Beitrag berechnen</h2>
  <p>Nutzen Sie unseren Tarifrechner, um den passenden Beitrag für Ihre Zahnzusatzversicherung zu finden:</p>
  <a href="https://ssl.barmenia.de/online-versichern/#/zahnversicherung/Beitrag?prd=Ausgezeichnete%2BZahnzusatzversicherung%2B&produkt=67015&sparte=BK&oabezeichnung=zahnversicherung&pid=Zahnversicherung&dom=www.barmenia.de&p0=234003&adm=00751651&em=james.davison&referrer=https:%2F%2Fwww.barmenia.de%2Fdeu%2Fbde_privat%2Fbde_produkte_privat%2Fbde_gesundheit%2Fzusatzversicherungen%2Fzahn%2Fuebersicht.xhtml" 
     class="cta" target="_blank" rel="noopener noreferrer">
    Beitrag jetzt berechnen

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p><strong>E-Mail:</strong> james.davison@barmenia.de</p>
    <p><strong>Telefon:</strong> 017681230236</p>
    <p><strong>Adresse:</strong> Ringstrasse 30, 63179 Obertshausen</p>
  </section>

  <footer>
    <p>&copy; 2025 ZahnFit – Alle Rechte vorbehalten.</p>
    <p><a href="#">Impressum</a> | <a href="#">Datenschutz</a></p>
  </footer>

</body>
</html>
