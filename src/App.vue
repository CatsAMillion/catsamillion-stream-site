<template>
  <div id="app">
    <Navi />
    <router-view/>
  </div>
</template>
<script>
import Navi from '@/components/Navi.vue'

export default {
  name: 'App',
  components: {
    Navi
  }
}
</script>

<style lang="scss">
  html {
    height: 100vh;
  }

  #app {
    height: 100vh;
  }

  a {
    color: black !important;
    > span {
      color: black;
    }
  }

  a:hover {
    color: pink !important;
    > span:hover {
      color: pink;
    }
  }

</style>
