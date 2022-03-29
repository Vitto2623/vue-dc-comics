<template>
  <div id="app">
    <!--Header.vue-->
    <Header />
    <!--Jumbotron.vue-->
    <Jumbotron />
    <main>
      <!--Contents.vue-->
    <Contents />
      <!--Component chiamato Elements.vue-->
    <Elements />
    </main>
    <!--TopFooter.vue-->
    <TopFooter />
    <!--BottomFooter.vue-->
    <BottomFooter />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Contents from './components/Contents.vue'
import TopFooter from './components/TopFooter.vue'
import BottomFooter from './components/BottomFooter.vue'
import Elements from './components/Elements.vue'
import Jumbotron from './components/Jumbotron.vue'
export default {
  name: 'App',
  components: {
    Header,
    Contents,
    TopFooter,
    Elements,
    BottomFooter,
    Jumbotron
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Arabic:wght@400;500&display=swap');
body{
  font-family: 'IBM Plex Sans Arabic', sans-serif;
  min-width: 1900px;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
