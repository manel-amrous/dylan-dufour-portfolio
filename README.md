<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio de Dylan, développeur web spécialisé dans la création de sites modernes et dynamiques.">
  Dylan -  Mon Portfolio
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
    <p>Je suis Dylan DUFOUR, un développeur web passionné par la création de sites web dynamiques et modernes.
    J'ai beaucoup de compétences et connaissances dans ce domaine, j'ai des compétences dans le réseau, la virtualisation, Active Directory, GLPI </p>
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
  </section>

  <section id="contact">
    <h2>Contactez-moi</h2> Pour plus de renseignements contactez-moi par 
    mail: dylan.dufour@laplateforme.io
    linkedin: https://www.linkedin.com/in/dylan-dufour-0bb0ba273/  instagram: https://www.instagram.com/


<button type="submit"></button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024  - Tous droits réservés</p>
  </footer>
</body>
</html>


<style>

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

header nav ul {
  list-style: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

#hero {
  background-color: #0056b3;
  color: #fff;
  padding: 60px 20px;
  text-align: center;
}

#hero h1 {
  font-size: 36px;
}

#projects {
  display: flex;
  justify-content: space-around;
  margin: 20px;
}

.project-card {
  width: 30%;
  background-color: #fff;
  padding: 20px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.project-card img {
  max-width: 100%;
  height: auto;
}

button {
  background-color: #333;
  color: #fff;
  padding: 10px 15px;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: #444;
}

/* Animations */
#hero {
  opacity: 0;
  animation: fadeIn 2s forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
  }
}
</style>

# dylan-dufour-portfolio
Portfolio
