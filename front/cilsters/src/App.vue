<template>
  <div id="app">
    <Sidebar/>
    <main> 
       <router-view/>
    </main>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Sidebar
  }
}
</script>

<style lang="scss">


</style>
