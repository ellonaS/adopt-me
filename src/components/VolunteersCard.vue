<template>
    
  <b-card
    header="VOLUNTEERS"
    header-text-variant="white"
    header-tag="header"
    header-bg-variant="primary"
  >
  <b-card-img id="girl" :src="require('../assets/img/girl.png')" alt="Image"></b-card-img>
  <b-card-body id="body">
    <b-card-text>Amazing people, doing the difference every single day. Join us now and be part of the community that is changing the world</b-card-text>
    <b-button variant="outline-primary">JOIN US</b-button>
  </b-card-body>
  </b-card>


</template>

<script>
export default {
    name: "volunteers-card"
}
</script>

<style scoped>
div.card-body {
    padding: 0px
}
p.card-text{
    padding: 20px
}
</style>