<template>
  <div>
    <b-card
      overlay
      :img-src="require('../assets/img/dogs.jpg')"
      img-alt="Card Image"
      text-variant="white"
    >
      <div id="darken">
        <div class="text">
          <b-card-title>This is your new family!</b-card-title>
          <b-button variant="outline-light">ADOPT NOW</b-button>
        </div>
      </div>
    </b-card>
  </div>
</template>

<script>
export default {
  name: "adopt-card"
};
</script>

<style scoped>
.card-img-overlay {
  padding: 0;
}
#darken {
  background: rgba(0, 0, 0, 0.7);
  padding: 0;
  margin: 0;
  position: absolute;
  bottom: 0;
  width: 100%;
  padding: 2% 2% 2% 5%;
}
</style>
