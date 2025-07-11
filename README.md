<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nice Info - Dossier Spécial</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f7f9fc;
      color: #333;
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    header {
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/3/3d/Nice_vue_generale.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 100px 20px;
      position: relative;
    }

    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background-color: rgba(0,0,0,0.4);
    }

    header h1, header p {
      position: relative;
      z-index: 1;
    }

    header h1 {
      font-size: 3em;
      animation: fadeIn 2s ease-in-out;
    }

    header p {
      font-size: 1.2em;
      animation: fadeIn 2.5s ease-in-out;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      padding: 15px 25px;
      display: block;
      color: #b90000;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: #ffe6e6;
    }

    .container {
      max-width: 900px;
      margin: 50px auto;
      background-color: white;
      padding: 40px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
      animation: slideUp 0.8s ease-in-out;
    }

    h2 {
      color: #b90000;
      margin-bottom: 15px;
    }

    .date {
      font-size: 0.9em;
      color: #888;
      margin-bottom: 20px;
    }

    blockquote {
      font-style: italic;
      background-color: #fce4e4;
      padding: 15px;
      margin: 20px 0;
      border-left: 5px solid #b90000;
    }

    footer {
      text-align: center;
      color: #999;
      font-size: 0.8em;
      padding: 20px;
      background-color: #f1f1f1;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Nice Info Journal</h1>
    <p>Dossier Spécial : Dangers des médicaments détournés chez les jeunes</p>
  </header>

  <nav>
    <a href="#">Accueil</a>
    <a href="#">Santé</a>
    <a href="#">Faits divers</a>
    <a href="#">Prévention</a>
    <a href="#">Témoignages</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <h2>Une jeunesse en danger : les overdoses se multiplient à Nice</h2>
    <p class="date">Mis à jour le 10 juillet 2025 - 23h45</p>

    <p> oh lina habdalah de abbatoirs te une pute rend le telephone a wasim</p>

    <p>Selon le CHU de Nice, les admissions aux urgences pour consommation excessive de médicaments sans ordonnance sont en nette augmentation depuis le début de l’année. Parmi les substances les plus souvent en cause : le tramadol, le Xanax, ou encore des anti-nauséeux comme le métoclopramide, pris pour leurs effets secondaires hallucinogènes.</p>

    <blockquote>
      "Je ne pensais pas que ça pouvait aller aussi loin... C'était pour s'amuser, mais on a vite perdu le contrôle." — Léo, 16 ans, ancien consommateur.
    </blockquote>

    <h3>Les médecins tirent la sonnette d'alarme</h3>
    <p>"Ce que nous voyons aux urgences est inquiétant. Ces jeunes pensent que les médicaments sont inoffensifs car vendus en pharmacie. En réalité, combinés ou pris à forte dose, les risques sont mortels", témoigne le docteur Navarro du service toxicologie de l’hôpital Pasteur.</p>

    <h3>Une campagne de prévention en cours</h3>
    <p>Face à cette situation, la mairie de Nice a annoncé le lancement d’une campagne de sensibilisation dans tous les collèges et lycées. Des ateliers, conférences et témoignages d’anciens victimes sont au programme dès la rentrée prochaine.</p>

    <blockquote>
      "Mon fils n'avait que 14 ans. Il a trouvé des cachets dans une pharmacie de famille... Si j'avais su, j’aurais tout enfermé." — Témoignage anonyme d’une mère niçoise.
    </blockquote>

    <h3>Que faire en cas de doute ?</h3>
    <p>Parents, éducateurs, jeunes : en cas de comportement suspect ou de symptômes inquiétants, n’attendez pas. Appelez immédiatement le 15 ou rendez-vous aux urgences les plus proches.</p>
  </div>

  <footer>
    &copy; 2025 Nice Info Journal. Tous droits réservés.
  </footer>
</body>
</html>
