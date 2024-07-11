<template>
  <HeaderComponent/>
  <MainContent/>
  <SliderComponent/>
  <FaqBlock/>
  <FooterBlock/>
</template>

<script>
import HeaderComponent from './components/Header.vue'
import MainContent from './components/MainBlock.vue'
import SliderComponent from './components/SliderComponent.vue'
import FaqBlock from './components/FaqBlock.vue'
import FooterBlock from './components/FooterBlock.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContent,
    SliderComponent,
    FaqBlock,
    FooterBlock
  }
}
</script>

<style lang="scss">
body.fixed{
  overflow: hidden;
}
html, body, h1, h2, h3, h4, h5, h6{
  margin: 0;
  padding: 0;
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
}
*{
  box-sizing: border-box;
  outline: none;
  transition:all 0.3s;
}
</style>
