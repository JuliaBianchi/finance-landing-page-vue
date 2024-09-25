<script >
import ContentComponent from './components/ContentComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';

export default {
  components: {
    'header-component': HeaderComponent,
    'content-component' : ContentComponent
  }
}

</script>

<template>
  <body>
    <header-component/>
    <content-component/>
  </body>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Overpass:ital,wght@0,100..900;1,100..900&display=swap');

body{
  height: 100vh;
  padding: 0;
  margin: 0;
  background-color: #1D1D1D;
  font-family: 'Overpass', sans-serif;
}

</style>
