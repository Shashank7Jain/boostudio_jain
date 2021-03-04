<template>
  <div>
   <Header />
   <Business_Enquiries />
   <How_Can_We />
  <curves />
  <Footer />
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Business_Enquiries from './components/Business_Enquiries.vue';
import How_Can_We from './components/How_Can_We.vue';
import Curves from './components/Curves.vue';
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Business_Enquiries,
    How_Can_We,
    Curves,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
