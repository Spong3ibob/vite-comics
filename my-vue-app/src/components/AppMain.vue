<script>
import ImageMain from './ImageMain.vue';
export default {
  components:{
    ImageMain
  },
  data() {
    return {
      content:"--> Content goes here <--"
    }
  }
}
</script>

<template>
  <ImageMain/>
  <main>
    <h1> {{content}} </h1>
  </main>
</template>

<style scoped>
h1{
  color: white;
}
</style>