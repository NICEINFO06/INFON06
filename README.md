<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alerte Prioritaire - Lina Habdal</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #0d0d0d;
      color: white;
      overflow-x: hidden;
    }
    header {
      background-color: #8b0000;
      padding: 1rem;
      text-align: center;
      border-bottom: 2px solid #ff0000;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 2px;
    }
    .alert-bar {
      background: linear-gradient(90deg, red, darkred);
      color: white;
      padding: 0.5rem;
      text-align: center;
      animation: flash 1.5s infinite alternate;
    }
    @keyframes flash {
      0% { background-color: #8b0000; }
      100% { background-color: #ff0000; }
    }
    .content {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .photo {
      float: right;
      width: 250px;
      margin-left: 2rem;
      filter: blur(4px);
      background: #222;
      height: 320px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #aaa;
      font-style: italic;
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
    .footer {
      background: #111;
      text-align: center;
      padding: 1rem;
      font-size: 0.8rem;
      color: #888;
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
  </style>
</head>
<body>
  <header>
    <h1>AGENCE EUROPÉENNE DE SÉCURITÉ TRANSFRONTALIÈRE</h1>
  </header>
  <div class="alert-bar">
    🔴 AVIS DE RECHERCHE PRIORITAIRE - INDIVIDU DANGEREUX 🔴
  </div>
  <div class="content">
    <h2>Dossier N° 4381-XFR-ALRM</h2>
    <div class="photo">Photo floutée</div>
    <table>
      <tr><td><strong>Nom :</strong></td><td>Lina Habdal</td></tr>
      <tr><td><strong>Taille :</strong></td><td>1m65</td></tr>
      <tr><td><strong>Cheveux :</strong></td><td>Noirs, mi-longs</td></tr>
      <tr><td><strong>Yeux :</strong></td><td>Marron</td></tr>
      <tr><td><strong>Dernier lieu confirmé :</strong></td><td>Polygone Riviera, Cagnes-sur-Mer</td></tr>
      <tr><td><strong>Zone suspectée :</strong></td><td>Secteur des abattoirs, Nice</td></tr>
      <tr><td><strong>Dangerosité :</strong></td><td class="danger-level">⚠️⚠️⚠️⚠️⚠️ Extrême</td></tr>
      <tr><td><strong>Faits reprochés :</strong></td><td>Vol aggravé (téléphone), résistance aux forces armées, fuite, comportement violent</td></tr>
    </table>
    <button class="report-button">SIGNALER CETTE PERSONNE</button>
  </div>
  <div class="footer">
    © 2025 AEST | Portail officiel fictif pour usage cinématographique uniquement
  </div>
</body>
</html>
