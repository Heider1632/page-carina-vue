<template>
  <div id="app">
    <navbar />
    <home />
    <intro />
    <divider />
    <footer />
  </div>
</template>

<script>
import navbar from './components/navbar';
import footer from './components/footer';
import home from './components/home';
import intro from './components/sections/intro';
import divider from './components/sections/divider';
export default {
  name: 'app',
  components: {navbar, footer, home, intro, divider},
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">

</style>
