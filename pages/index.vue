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
    </section>
    <section id="moncv">
      <h2>Mon CV</h2>
    </section>
    <section id="mesprojets">
      <h2>Mes projets</h2>
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
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.navbar {
  position: absolute;
  top: 0px;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

section {
  display: block;
}

h2 {
  text-align: left;
  padding: 20px;
}

.accueil {
  background-image: url('../components/img-dev.jpg');
}
</style>
