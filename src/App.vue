<template>
  <div id="app">
    <Hero
      msg=" Buefy is a lightweight library of responsive UI components for Vue.js based on Bulma framework and design."
      title="Welcome to Buefy library."
    />
    <Contact title="Contact us."/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue';
import Contact from './components/Contact.vue';

export default {
  name: 'App',
  components: {
    Hero,
    Contact,
  },
};
</script>

<style lang="scss">

</style>
