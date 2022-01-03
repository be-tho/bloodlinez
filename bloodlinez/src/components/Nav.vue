<template>
  <div>
    <header>
      <nav id="nav">
        <a href=""><h1>BloodLineZ</h1></a>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/rules">Rules</router-link></li>
          <li><router-link to="/about">About</router-link></li>
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

</style>