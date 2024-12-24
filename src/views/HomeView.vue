<template>
  <div class="home">
    <header class="hero-section">
      <h1 class="display-4">Práctica 1</h1>
      <p class="lead">Práctica 1 del módulo VUE del diplomado en FullStack </p>
      <p>Integrante(s):</p>
      <ul>
        <li>Iurii Chernichenko</li>
      </ul>
      <p>Ver <a href="contactos">Agenda de Contactos</a></p>
    </header>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
