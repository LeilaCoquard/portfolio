<template>
  <div class="container">
    <nav class="navbar is-light" role="navigation" aria-label="main navigation">
      <div class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#accueil">Accueil</a>
          <a class="navbar-item" href="#apropos">A propos</a>
          <a class="navbar-item" href="#mescompetences">Mes compétences</a>
          <a class="navbar-item" href="#mesprojets">Mes projets</a>
          <a class="navbar-item" href="#contact">Contact</a>
        </div>
      </div>
    </nav>
    <section id="accueil">
      <h1 class="title-presentation">Leïla Coquard</h1>
      <h2 class="subtitle-presentation">Développeuse web Junior</h2>
    </section>

    <section id="apropos">
      <h2>A propos</h2>
      <h3>Leïla Coquard, 31 ans, en reconversion professionnelle</h3>
      <h4>Développeuse web Junior</h4>
      <p>
        Après des études en statistiques, spécialisée en actuariat, j'ai intégré
        le milieu professionnel en tant qu'actuaire pendant 6 ans. Cette
        expérience a eu pour effet de me faire murrir, de développer mon sens du
        travail bien fait et d'apprivoiser les relations humaines en entreprise.
        Ces 6 ans fut entrecoupé d'un voyage d'un an autour du monde. C'est fou
        tout ce qu'on peut apprendre pendant un voyage, repenser complétement
        ses schemas de pensées. blabla...
      </p>
      <a
        class="button is-primary"
        href="/CV-DevFront-LCoquard2019.pdf"
        target="_blank"
        >Mon CV</a
      >
    </section>
    <hr />
    <section id="mescompetences">
      <h2>Mes compétences</h2>
      <p><fa-icon icon="map-marker-alt"></fa-icon></p>
    </section>
    <hr />

    <section id="mesprojets">
      <h2>Mes projets</h2>

      <div class="row">
        <!--projet2-->
        <div class="column card">
          <div class="card-image">
            <figure class="image P2">
              <img src="../components/Image-P2.png" alt="Projet2 image" />
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-content">
                <p class="title is-4">Formation : projet 2</p>
                <p class="subtitle is-6">Site Wordpress</p>
              </div>
            </div>

            <div class="content">
              <p>Intégrez un thème Wordpress pour un client</p>
              <a href="https://chaletsetcaviar.leilacoquard.fr">Site</a>
              <br />
              <time datetime="2018-11-1">Novembre 2018</time>
            </div>
          </div>
        </div>

        <!--Projet6-->
        <div class="column card">
          <div class="card-image">
            <figure class="image P6">
              <img src="../components/Image-P6.png" alt="Projet6 image" />
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-content">
                <p class="title is-4">Formation : projet 6</p>
                <p class="subtitle is-6">Jeu de plateau en JS</p>
              </div>
            </div>

            <div class="content">
              <p>
                Ce projet consiste à créer un jeu en ligne en JavaScript dans
                lequel 2 joueurs évoluent chacun leur tour pour s'affronter.
              </p>
              <a href="http://www.projet6.leilacoquard.fr">Site</a>
              <br />
              <time datetime="2019-3-1">Mars 2019</time>
            </div>
          </div>
        </div>
      </div>
    </section>
    <hr />

    <section id="contact">
      <h2>Contact</h2>
      <h3>N'hésitez pas à me contacter pour plus d'informations</h3>
      <div id="general-contact">
        <div id="detail-contact">
          <p>Leïla Coquard</p>
          <p>
            <fa-icon icon="map-marker-alt"></fa-icon>
            Montreuil, France
          </p>
          <p>
            <fa-icon icon="phone-alt"></fa-icon>
            07.68.51.99.89
          </p>
          <p>
            <fa-icon icon="envelope"></fa-icon>
            leilacoquard@gmail.com
          </p>
        </div>

        <!-- Formulaire de contact -->
        <div id="form-contact">
          <form action="https://api.staticforms.xyz/submit" method="post">
            <input
              type="hidden"
              name="accessKey"
              value="a958579f-3736-46f5-b722-24322cdb78f3"
            />
            <div class="field">
              <label class="label">Nom</label>
              <input class="input" name="name" placeholder="Mon nom" />
            </div>
            <div class="field">
              <label class="label">Email</label>
              <div class="control has-icons-right">
                <input
                  class="input"
                  type="email"
                  name="email"
                  placeholder="XXX@xxx.com"
                />
                <span class="icon is-small is-left">
                  <i class="fas fa-envelope"></i>
                </span>
                <span class="icon is-small is-right">
                  <i class="fas fa-exclamation-triangle"></i>
                </span>
              </div>
            </div>
            <div class="field">
              <label class="label">Message</label>
              <div class="control">
                <textarea
                  class="textarea"
                  name="message"
                  placeholder="Je vous contacte pour ..."
                ></textarea>
              </div>
            </div>
            <div class="field is-grouped">
              <div class="control">
                <button class="button is-primary" type="submit">Envoyer</button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script></script>

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

.title-presentation {
  font-family: 'Beth Ellen', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle-presentation {
  font-family: 'Beth Ellen', Arial, sans-serif;
  font-weight: 300;
  font-size: 50px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align: center;
}

section {
  display: block;
  float: left;
  width: 100%;
  margin: 30px 0px;
}

hr {
  border: 1px solid rgba(118, 118, 118, 0.673);
}

h2 {
  text-align: left;
  padding: 20px;
  font-size: 30px;
}

#accueil {
  padding: 100px;
  position: relative;
}
#accueil::before {
  content: '';
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
  opacity: 0.3;
  background-image: url('../components/img-dev.jpg');
  background-repeat: no-repeat;
  background-size: cover;
}

#apropos p {
  margin: 20px 0;
}

.row {
  margin: -5px;
}

.column {
  float: left;
  width: 25%;
}

.card {
  margin: 8px;
  height: 500px;
}

.card:hover {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.card-image img {
  height: 200px;
}

.title.is-4 {
  font-size: 1.4rem;
}

#detail-contact {
  margin: 30px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

#form-contact {
  margin: 10px;
  width: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

label {
  text-align: left;
}
</style>
