<template>
  <div id="app">
    <!-- header -->
    <Header />
    <!-- main -->
    <main>
    <ContentMain />
    <!-- bonus -->

    </main>

    <!-- footer -->
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ContentMain from './components/ContentMain.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    ContentMain,
    Footer,
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
