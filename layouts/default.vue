<template>
    <div>
      <HeaderAndFirstScreen />
      <NuxtPage />
      <Footer />
    </div>
  </template>
  
  <script>
  import HeaderAndFirstScreen from '~/components/HeaderAndFirstScreen.vue';
  import Footer from '~/components/Footer.vue';
  
  export default {
    components: {
      HeaderAndFirstScreen,
      Footer,
    },
  };
  </script>