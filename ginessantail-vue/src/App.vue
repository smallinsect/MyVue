<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <!-- <b-container>
      <navbar />
    </b-container> -->
    <navbar />
    <b-container>
      <router-view/>
    </b-container>
  </div>
</template>

<script>

import Navbar from './views/layout/Navbar.vue';

export default {
  components: { Navbar },
  data() {

  },
};

</script>

<style lang="scss">

</style>
