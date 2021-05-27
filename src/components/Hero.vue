<template>
  <div class="hero is-warning is-fullheight is-bold">
    <div class="hero-body">
      <div class="hero-container has-text-centered">
        <h1 class="title">{{ title }}</h1>
        <h1 class="is-size-5">{{ msg }}</h1>
        <a href="#contactForm" class="button m-top-20"> Contact us </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    title: String,
    msg: String,
  },
};
</script>

<style scoped lang="scss">
.m-top-20 {
  margin-top: 20px;
  color: black;
}
.hero-body {
  justify-content: center;
}
</style>
