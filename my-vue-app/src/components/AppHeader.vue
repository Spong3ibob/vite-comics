<script>
export default {
  data() {
    return {
      navigations:[
        {
          name:"CHARATERS",
          status:false,
        },
        {
          name:"COMICS",
          status:true,
        },
        {
          name:"TV",
          status:false,
        },
        {
          name:"GAMES",
          status:false,
        },
        {
          name:"COLECTIBLES",
          status:false,
        },
        {
          name:"VIDEOS",
          status:false,
        },
        {
          name:"FANS",
          status:false,
        },
        {
          name:"NEWS",
          status:false,
        },
        {
          name:"SHOP",
          status:false,
        },  
    ]
    }
  }
}
</script>

<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="">
    <nav>
      <li v-for="navigation in navigations" :class="{active: navigation.status}">{{navigation.name}}</li>
    </nav>
</header>
</template>

<style lang="scss">
nav{
  padding-right: 40px;
}
li{
  padding: 50px 15px;
}
.active{
    color: var(--primary-color);
    border-bottom: 3px solid;
}
</style>