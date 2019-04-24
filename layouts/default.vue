<template>
  <div>
    <Header @sidenavToggle='show = !show'/>
    <TheSidenav :show='show' @close='show = !show'/>
    <nuxt />
  </div>
</template>
<script>
import Header from '@/components/Navigation/TheHeader'
import TheSidenav from '@/components/Navigation/TheSidenav'
export default {
  components: {
    Header, 
    TheSidenav
  },
  data(){
    return {
        show: false
    }
  }

}
</script>

<style>
html {
  font-family: 'Open Sans', sans-serif;
}
body {
  margin: 0;
}
</style>
