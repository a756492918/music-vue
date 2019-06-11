<template>
  <div id="app">
    <Mheader></Mheader>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<script>
import Mheader from './components/header/header.vue'
import Tab from './components/tab/tab.vue'
export default {
  name: 'App',
  data () {
    return {

    }
  },
  components: {
    Mheader,
    Tab
  }
}
</script>
<style>
</style>
