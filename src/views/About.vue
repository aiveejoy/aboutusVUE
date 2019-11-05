<template>
  <div class="about">
    <h1>About the Developers</h1>
    <div class="row">
      <div v-for="(member, index) in group" :key="index" class="col-3">
        <devs  :name="member['name']" :img="member['src']" :position="member['position']"></devs>
      </div>        
    </div>        
  </div>
</template>

<script>
import devs from '@/components/Dev'
export default {
  components: {
    devs
  },
  data(){
    return{
      group: [
        {name: "Mary Grace Tiburillo", src: require('@/assets/tibs.png'), position: "Project Manager"},
        {name: "Jessa Jalandoni", src: require('@/assets/isang.png'), position: "Front End"},
        {name: "Geneva Rivas", src: require('@/assets/Gen3.png'), position: "Back End Developer"},
        {name: "Ivy Joy Devilleres", src: require('@/assets/byang.png'), position: "Assistant Back End Developer"}
      ]
    }
  }
}
</script>
<style>
</style>
