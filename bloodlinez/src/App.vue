<template>
  <div id="app">
    <Nav />
    <main>
      <router-view/>
    </main>
    <Footer />
  </div>
</template>
<script>
import Footer from "./components/Footer";
import Nav from "./components/Nav";
export default {
  name: 'App',
  components: {
    Footer,
    Nav
  }
}
</script>