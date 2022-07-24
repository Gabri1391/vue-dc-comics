<template>
  <BaseHeader />
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue"

export default {
  name: 'App',
  components: {
    BaseHeader,
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
