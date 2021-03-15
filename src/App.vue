<template>
  <div id="app">
    <topnav/>
    <router-view/>
    <footerArea/>
  </div>
</template>

<script>
// @ is an alias to /src
import topnav from '@/components/static/topnav.vue'
import footerArea from '@/components/static/footer.vue'

export default {
  name: '',
  components: {
    topnav,
    footerArea
  }
}
</script>

<style>
#app {
  font-family: 'Raleway', sans-serif;
}
</style>
