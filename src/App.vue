<template lang="pug">
  #app
    Top
    #left
      Menu
      Update
    #right
</template>

<script>
import Top from './components/Top'
import Menu from './components/Menu'
import Update from './components/Update'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    Update
  }
}
</script>
