<script>
export default {
  data() {
    return {
      navigations:[
        "CHARATERS",
        "COMICS",
        "TV",
        "GAMES",
        "COLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP"
    ]
    }
  }
}
</script>

<template>
  <img src="../assets/img/dc-logo.png" alt="">
  <nav>
    <li v-for="navigation in navigations" class="active">{{navigation}}</li>
  </nav>
</template>

<style lang="scss">
nav{
  padding-right: 40px;
}
li{
  padding: 50px 15px;
  &.active:hover{
    color: var(--primary-color);
    border-bottom: 3px solid;
  }
}
</style>