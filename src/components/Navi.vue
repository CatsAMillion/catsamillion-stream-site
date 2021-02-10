<template>
  <b-navbar>
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <p class="brand">CatsAMillion</p>
      </b-navbar-item>
    </template>
    <template #start>
      <b-navbar-item tag="router-link" :to="{ path: '/about' }">
        About
      </b-navbar-item>
      <b-navbar-item tag="router-link" :to="{ path: '/polls' }">
        Polls
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {
  name: 'navi',
};
</script>

<style scoped lang="scss">
@font-face {
  font-family: 'WildySans';
  src: url('/Wildy-Sans.ttf') format('truetype');
}
.brand {
  font-family: 'WildySans', cursive;
  font-size: 3rem;
}
</style>
