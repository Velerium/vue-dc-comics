<template>
  <div id="app">
    <Header />
    <Content />
    <BlueSection />
    <Footer />
    <BottomSection />
  </div>
</template>

<script>
  import Header from './components/Header.vue';
  import Content from './components/Content.vue';
  import BlueSection from './components/Blue-section.vue';
  import Footer from './components/Footer.vue';
  import BottomSection from './components/Bottom-section.vue';


  export default {
    name: 'App',
    components: {
      Header,
      Content,
      BlueSection,
      Footer,
      BottomSection
    }
}
</script>

<style lang="scss">

@import './style/app';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container {
  width: 1200px;
  margin: 0 auto;
  display: flex;
}

</style>
