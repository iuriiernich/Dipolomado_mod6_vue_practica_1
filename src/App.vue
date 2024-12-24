<template>

  <nav class="navbar navbar-expand-lg bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">Contactos</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <router-link to="/" class="nav-link">Home</router-link>
          <router-link to="/contactos" class="nav-link">Agenda de Contactos</router-link>
        </div>
      </div>
    </div>
  </nav>
  <div class="container">
    <router-view/>
  </div>

</template>

<style  lang="scss">
.bg-primary {
    --bs-bg-opacity: 1;
    background-color: #ffc107 !important;
}
</style>
