<template>
  <div>
    <header>
      <nav id="nav">
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
          <i class="fas fa-bars"></i>
        </label>
        <router-link to="/"><h1 class="nav__h1">BloodLineZ</h1></router-link>
        <ul class="nav__ul">
          <li><router-link to="/" >Home</router-link></li>
          <li><router-link to="/rules" >Rules</router-link></li>
          <li><router-link to="/views" >Views</router-link></li>
          <li><router-link to="/videos" >Videos</router-link></li>
          <li><router-link to="/about" >About</router-link></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: "Nav"
}
</script>
<style scoped>
  a.router-link-exact-active {
    background: #b01414;
    transition: .5s;
    color: white;
  }
</style>
