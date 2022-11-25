<script>
import ImageMain from './ImageMain.vue';
import CardMain from './CardMain.vue';

export default {
  components:{
    ImageMain,
    CardMain
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
    <div class="container-cards">
      <CardMain />
    </div>
  </main>
</template>

<style scoped>
h1{
  color: white;
}
</style>