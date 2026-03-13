<template >
  <div class="min-h-screen bg-linear-to-br from-gray-900 via-blue-900 to-gray-900 text-white">
    <Navbar />
    <Hero />
    <Services />
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Services from './components/Services.vue'

import { nextTick, onMounted,ref } from 'vue';
import AOS  from 'aos';
import 'aos/dist/aos.css';
export default {
  components: {
  Navbar,
  Hero,
  Services
  },
  setup() {
    const loading = ref(true)

    onMounted(() => {
      nextTick();
      AOS.init({
        duration: 800,
        once: false,
        offset: 100,
        easing: 'ease-in-out',
        
      });
      setTimeout(() => {
        loading.value = false
      }, 800)
    })
  }
  
}
</script>
<style >
  
</style>