<template lang="pug">
  #app
    Top
    #left
      Menu
    #right
</template>

<script>
import Top from './components/Top'
import Menu from './components/Menu'

export default {
  name: 'App',
  components: {
    Top,
    Menu
  }
}
</script>
