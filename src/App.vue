<template lang="pug">
#app
  top
  #content
    #left
      //- 不能用小 m 因為 menu 為 vue 預設字
      Menu
      update
    #right
      mar
      Main
  Footer
</template>

<script>
import top from './components/top.vue'
import Menu from './components/menu.vue'
import update from './components/update.vue'
import mar from './components/marquee.vue'
import Main from './components/main.vue'
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    top,
    Menu,
    update,
    mar,
    Main,
    Footer
  }
}
</script>
