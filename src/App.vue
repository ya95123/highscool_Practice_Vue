<template lang="pug">
  #app
    Top
    #left
      Menu
      Update
    #right
      Marquee
      #content
        Main(v-if="page === 'main'")
</template>

<script>
import Top from './components/Top'
import Menu from './components/Menu'
import Update from './components/Update'
import Marquee from './components/Marquee'
import Main from './components/Main'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    Update,
    Marquee,
    Main
  },
  data () {
    return {
      page: 'main'
    }
  }
}
</script>
