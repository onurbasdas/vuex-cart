<template>
  <div id="app" class="container">
    <nav-bar></nav-bar>
    <router-view></router-view>
  </div>
</template>

<script>
import NavBar from './components/Navbar'
export default {
  name: 'app',
  components: {
    NavBar
  },
  data () {
    return {}
  }
}
</script>
