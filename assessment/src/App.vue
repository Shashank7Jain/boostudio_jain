<template>
  <div>
    <Header />
    <Business_Enquiries />
    <How_Can_We />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Business_Enquiries from "./components/Business_Enquiries.vue";
import How_Can_We from "./components/How_Can_We.vue";

import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Business_Enquiries,
    How_Can_We,

    Footer,
  },
};
</script>

<style>
* {
  font-family: "Segoe UI";
}
hr {
  border-top: 1px solid #e1e2e3;
}
input:focus,
select:focus,
textarea:focus,
button:focus {
  outline: none;
}
</style>
