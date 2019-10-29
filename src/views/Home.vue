<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/toothlogo.png">
    <HelloWorld msg="ToothBook"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style>
img {
  height: 500px;
  width: 500px;
}
</style>
