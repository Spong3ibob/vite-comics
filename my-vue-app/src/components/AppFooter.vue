<script>
import HeaderFooter from "../components/HeaderFooter.vue";
import MainFooter from  "../components/MainFooter.vue";
import FooterButtom from  "../components/FooterButtom.vue";

export default {
  components:{
    HeaderFooter,
    MainFooter,
    FooterButtom
  },
  data() {
    return {

    }
  }
}
</script>

<template>
  <header>
   <HeaderFooter/> 
  </header>
  <main>
    <MainFooter/>
  </main>
  <footer>
    <FooterButtom/>
  </footer>
   
</template>

<style lang="scss" scoped>
header{
  height: 160px;
  width: 100%;
  background-color: var(--primary-color);
}
main{
  height: 370px;
  width: 100%;
  background-image: url(../assets/img/footer-bg.jpg);
}
footer{
  height: 100px;
  width: 100%;
  background-color: var(--footer-buttom);
}
</style>