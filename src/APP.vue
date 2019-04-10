<template>
  <div>
    <Header></Header>
    <Home></Home>
  </div>
</template>
<router-view></router-view>
<script>
import Home from './pages/home/Home.vue'
import Header from './pages/header/Header'
import Footer from './pages/footer/Footer'
export default {
  name: 'app',
  components: {
    Home,
    Header,
    Footer
  }
}
</script>

<style>
</style>
