<template>
  <div class="container">
    <nav class="navbar is-light" role="navigation" aria-label="main navigation">
      <div class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item">Accueil</a>
          <a class="navbar-item">A propos</a>
          <a class="navbar-item">Mon CV</a>
          <a class="navbar-item">Mes projets</a>
          <a class="navbar-item">Contact</a>
        </div>
      </div>
    </nav>
    <section id="accueil">
      <h1 class="title">Leïla Coquard</h1>
      <h2 class="subtitle">Développeuse web Junior</h2>
    </section>

    <section id="apropos">
      <h2>A propos</h2>
      <h3>Leïla Coquard, 31 ans, en reconversion professionnelle</h3>
      <h4>Développeuse web Junior</h4>
      <p>Après des études en statistiques, spécialisée en actuariat, j'ai intégré le milieu professionnel en tant qu'actuaire pendant 6 ans. Cette expérience a eu pour effet de me faire murrir, de développer mon sens du travail bien fait et d'apprivoiser les relations humaines en entreprise. Ces 6 ans fut entrecoupé d'un voyage d'un an autour du monde. C'est fou tout ce qu'on peut apprendre pendant un voyage, repenser complétement ses schemas de pensées. blabla...</p>
    </section>
    <section id="moncv">
      <h2>Mon CV</h2>
    </section>
    <section id="mesprojets">
      <h2>Mes projets</h2>

      <div class="card">
        <div class="card-image">
          <figure class="image P6">
            <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image" />
          </figure>
        </div>
        <div class="card-content">
          <div class="media">
            <div class="media-content">
              <p class="title is-4">Projet OC 6</p>
              <p class="subtitle is-6">Jeu de plateau</p>
            </div>
          </div>

          <div class="content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris.
            <a
              href
            >blabla</a>
            <br />
            <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
          </div>
        </div>
      </div>
    </section>
    <section id="contact">
      <h2>Contact</h2>
    </section>
  </div>
</template>

<script>
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  /*display: flex;*/
  justify-content: center;
  align-items: center;
  text-align: center;
}

.navbar {
  position: absolute;
  top: 0px;
  width: 100%;
}

.navbar-item {
  margin: 5px 10px;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 70px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 40px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align: center;
}

section {
  display: block;
  width: 100%;
}

h2 {
  text-align: left;
  padding: 20px;
}

#accueil {
  background-image: url('../components/img-dev.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  padding: 100px;
}

.card {
  width: 25%;
}
</style>
