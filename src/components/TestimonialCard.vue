<template>
  <div>
    <b-card
      header="TESTIMONIAL OF THE MONTH"
      header-text-variant="white"
      header-tag="header"
      header-bg-variant="info"
      overlay
      :img-src="require('../assets/img/testimonial.jpg')"
      img-alt="Girl playing with a dog"
      img-bottom
    >
      <b-card-title id="title">Mangi, my best friend who saved my life</b-card-title>
      <b-button variant="info" class="mb-2" id="play" @click="$bvModal.show('bv-modal-example')">
        <b-icon icon="play" aria-hidden="true"></b-icon>
      </b-button>
      <b-modal id="bv-modal-example" hide-footer>
        <template v-slot:modal-title>Rescue pittie</template>
        <div class="embed-responsive embed-responsive-16by9">
          <iframe
            class="embed-responsive-item"
            src="https://www.youtube.com/embed/-Fvn9C6b6WE"
            allowfullscreen
          ></iframe>
        </div>
      </b-modal>
    </b-card>
  </div>
</template>

<script>
export default {
  name: "testimoinial-card"
};
</script>

<style scoped>
#title {
  position: absolute;
  bottom: 10%;
  color: white;
}
.card {
  box-shadow: 2px 2px 10px gray;
}
#play {
  position: absolute;
  bottom: 40%;
  left: 45%;
}
</style>
