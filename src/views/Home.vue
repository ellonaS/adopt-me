<template>
  <div class="home">
   <adopt-card> </adopt-card>
   <b-card-group>
   <volunteers-card> </volunteers-card>
   <testimonial-card> </testimonial-card>
   </b-card-group>
  </div>
</template>

<script>
// @ is an alias to /src
import AdoptCard from "@/components/AdoptCard";
import VolunteersCard from "@/components/VolunteersCard";
import TestimonialCard from "@/components/TestimonialCard";

export default {
  name: 'Home',
  components: {
    AdoptCard,
    VolunteersCard,
    TestimonialCard
  }
}
</script>

<style scoped>
div.card-deck {
  padding-left: 40px;
  padding-right: 40px;
  padding-top: 20px;

}
</style>
