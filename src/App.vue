<template>
  <div id="app">
    <BaseHeader />
    <TheMain />
    <TheTopFooter/>
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue"
import TheMain from "./components/TheMain.vue"
import TheTopFooter from "./components/TheFooter.vue"

export default {
  name: 'App',
  components: {
    BaseHeader,
    TheMain,
    TheTopFooter,
  
}

}
</script>

<style lang="scss">
body{
  font-family: 'Open Sans', sans-serif;
}

a{
  text-decoration: none;
}

ul li{
  list-style-type: none;
}

</style>
