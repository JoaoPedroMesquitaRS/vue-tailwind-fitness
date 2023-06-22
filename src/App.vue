<template>
  <div>
    <Header />
    <div class="flex">
      <Nav />
      <Dashboard />
    </div>
    
</div>
</template>

<script>

import Header from './components/Header.vue'
import Dashboard from './components/Dashboard.vue'
import Nav from './components/Nav.vue'
import Footer from './components/Footer.vue'

export default{
  components: {
    Header,
    Dashboard,
    Nav,
    Footer
  }
}

</script>

<style scoped>
</style>