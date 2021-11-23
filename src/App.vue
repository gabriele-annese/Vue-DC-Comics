<template>
  <div id="app">
    <!-- header -->
    <Header />
    <!-- main -->
    <ContentMain />
    <!-- footer -->
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ContentMain from './components/ContentMain.vue'

export default {
  name: 'App',
  components: {
    Header,
    ContentMain,
  }
}
</script>

<style lang="scss">
* {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
