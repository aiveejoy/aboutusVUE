<template>
  <div class="w-100">
    <b-card  :title="name" :img-src="img">
      <b-card-text>{{position}}</b-card-text>
    </b-card>
  </div>
</template>

<style>
card-img{
  width: 1px;
}
</style>

<script>
export default {
  props: {
    name: String,
    img: String,
    position: String
  }
};
</script>

