<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alerte Prioritaire - Enquête Sécurisée</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #0b0b0b;
      color: #f0f0f0;
      overflow-x: hidden;
    }
    header {
      background-color: #8b0000;
      padding: 1rem;
      text-align: center;
      border-bottom: 2px solid #ff0000;
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 2px;
    }
    .flashing-border {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      border: 4px solid red;
      box-sizing: border-box;
      animation: borderFlash 1.5s infinite alternate;
    }
    @keyframes borderFlash {
      0% { border-color: red; }
      100% { border-color: darkred; }
    }
    .alert-bar {
      background: linear-gradient(90deg, red, darkred);
      color: white;
      padding: 0.5rem;
      text-align: center;
      animation: flash 1.5s infinite alternate;
      font-weight: bold;
    }
    @keyframes flash {
      0% { background-color: #8b0000; }
      100% { background-color: #ff0000; }
    }
    .content {
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
    }
    .profile {
      display: flex;
      gap: 2rem;
      flex-wrap: wrap;
    }
    .photo {
      width: 280px;
      height: 340px;
      filter: blur(5px);
      background: #222;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #aaa;
      font-style: italic;
      border: 1px solid #444;
    }
    .details {
      flex: 1;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
    }
    td {
      padding: 0.5rem;
      border-bottom: 1px solid #333;
    }
    .danger-level {
      color: red;
      font-weight: bold;
    }
    .section {
      margin-top: 3rem;
    }
    .report-button {
      margin-top: 2rem;
      background: red;
      border: none;
      color: white;
      font-size: 1rem;
      padding: 1rem;
      width: 100%;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .report-button:hover {
      background: darkred;
    }
    .footer {
      background: #111;
      text-align: center;
      padding: 1rem;
      font-size: 0.8rem;
      color: #888;
      margin-top: 2rem;
    }
    .testimonial {
      background: #1a1a1a;
      border-left: 4px solid red;
      padding: 1rem;
      margin-top: 1rem;
      font-style: italic;
    }
  </style>
</head>
<body>
  <header>
    <div class="flashing-border"></div>
    <h1>PORTAIL EUROPÉEN DE RECHERCHE SÉCURITAIRE</h1>
  </header>
  <div class="alert-bar">
    🔴 AVIS DE RECHERCHE PRIORITAIRE – INDIVIDUS DANGEREUX 🔴
  </div>
  <div class="content">
    <h2>Dossier N° 4381-XFR-ALRM</h2>

    <div class="profile">
      <div class="photo">Photo floutée - Lina Habdallah</div>
      <div class="details">
        <h3>Lina Habdallah</h3>
        <table>
          <tr><td><strong>Âge :</strong></td><td>13 ans</td></tr>
          <tr><td><strong>Taille :</strong></td><td>1m65</td></tr>
          <tr><td><strong>Cheveux :</strong></td><td>Noirs, mi-longs</td></tr>
          <tr><td><strong>Yeux :</strong></td><td>Marron</td></tr>
          <tr><td><strong>Dernier lieu confirmé :</strong></td><td>Polygone Riviera, Cagnes-sur-Mer</td></tr>
          <tr><td><strong>Zone suspectée :</strong></td><td>Abattoirs, Nice</td></tr>
          <tr><td><strong>Dangerosité :</strong></td><td class="danger-level">⚠️⚠️⚠️⚠️⚠️ Extrême</td></tr>
          <tr><td><strong>Faits reprochés :</strong></td><td>Vol aggravé d’un téléphone, fuite policière, comportement violent</td></tr>
        </table>
      </div>
    </div>

    <div class="profile section">
      <div class="photo">Photo floutée - Andrei Ailloae</div>
      <div class="details">
        <h3>Andrei Ailloae</h3>
        <table>
          <tr><td><strong>Âge :</strong></td><td>14 ans</td></tr>
          <tr><td><strong>Yeux :</strong></td><td>Verts</td></tr>
          <tr><td><strong>Zone suspectée :</strong></td><td>Quartier Trachel, Nice</td></tr>
          <tr><td><strong>Activités signalées :</strong></td><td>Présence régulière sur site, comportements suspects, potentielle complicité</td></tr>
          <tr><td><strong>Statut :</strong></td><td class="danger-level">Personne à surveiller / Enquête ouverte</td></tr>
        </table>
      </div>
    </div>

    <div class="section">
      <h3>Témoignages reçus</h3>
      <div class="testimonial">
        "Je les ai vus ensemble près de la station de train a cagne-sur-mer, ils semblaient observer les passants de manière étrange on dirais que ils voulais les raquetter."
        <br />– Anonyme, 9 juillet 2025
      </div>
      <div class="testimonial">
        "Lina courais dans la gare de antibes avec deux amis filles a elles, elle etais tres etrange.
        
        ILS RISQUE TOUT LES DEUX J'USQUA 3 ANS D'EMPRISONEMENT ET 7600 EURO D'AMENDES"
        <br />– Témoin civil, 10 juillet 2025
      </div>
    </div>

    <button class="report-button">🔍 SIGNALER DES INFORMATIONS</button>
  </div>
  <div class="footer">
    © 2025 Portail AEST | POLICE MILLITAIRE DE LA FRANCE
  </div>
</body>
</html>

