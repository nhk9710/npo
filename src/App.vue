<template>
  <div id="q-app">
    <router-view />
  </div>
</template>
<script>
import AOS from 'aos'
import 'aos/dist/aos.css'
export default {
  name: 'App',
  mounted() {
    AOS.init({
      duration:500,
      delay:50
    });
  }
}
</script>
