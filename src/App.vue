<template>
  <Header></Header>
  <HeaderText></HeaderText>
  <Discover></Discover>
  <Deep></Deep>
  <Last></Last>
  <Footer></Footer>
</template>

<script>
import Header from './components/Header.vue'
import HeaderText from './components/HeaderText.vue'
import Discover from './components/Discover.vue'
import Deep from './components/Deep.vue'
import Last from './components/Last.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    HeaderText,
    Discover,
    Deep,
    Last,
    Footer // Add this line
  }
}
</script>

<style scoped>
</style>
