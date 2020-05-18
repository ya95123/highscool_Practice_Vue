<template lang="pug">
  #app
    Top
    #left
      Menu
      Update
    #right
      Marquee123
      #content
        Main(v-if="page === 'main'")
    Footer
</template>

<script>
import Top from './components/Top'
import Menu from './components/Menu'
import Update from './components/Update'
import Marquee123 from './components/Marquee'
import Main from './components/Main'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    Update,
    Marquee123,
    Main,
    Footer
  },
  data () {
    return {
      page: 'main'
    }
  }
}
</script>
