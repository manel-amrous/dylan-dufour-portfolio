<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio de [Votre Nom], développeur web spécialisé dans la création de sites modernes et dynamiques.">
  <title> Dylan - Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#about">À propos</a></li>
        <li><a href="#projects">Projets</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h1>Bienvenue sur mon portfolio</h1>
    <p>Je suis Dylan DUFOUR, un développeur web passionné par la création de sites web dynamiques et modernes.</p>
    <a href="#projects" class="btn">Voir mes projets</a>
  </section>

  <section id="about">
    <h2>À propos de moi</h2>
    <p>Je suis un développeur web avec une expérience dans la création de sites responsive et interactifs...</p>
  </section>

  <section id="projects">
    <h2>Mes projets</h2>
    <div class="project-card">
      <img src="projet1.jpg" alt="Projet 1">
      <h3>Nom du projet</h3>
      <p>Description du projet...</p>
    </div>
    <!-- Ajoutez d'autres cartes de projets ici -->
  </section>

  <section id="contact">
    <h2>Contactez-moi</h2>
    <form action="mailto:contact@votresite.com" method="POST" enctype="text/plain">
      <label for="email">Email :</label>
      <input type="email" id="email" name="email" required>
      <textarea id="message" name="message" placeholder="Votre message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Dylan - Tous droits réservés</p>
  </footer>
</body>
</html>


# dylan-dufour-portfolio
Portfolio
