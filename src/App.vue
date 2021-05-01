<template>
  <div id="app">
    <div id="nav" class="neon-font">
      <router-link to="/" class="btn">Home</router-link> |
      <router-link to="/about" class="btn">About</router-link>
    </div>
    <router-view/>

  </div>
</template>

<style lang="scss">

@import "~@/scss/components/Navbar.scss";

</style>
