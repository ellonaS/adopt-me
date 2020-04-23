<template>
  <div class="home">
   <adopt-card id="adopt"> </adopt-card>
   <div class="margin" id="home-content">
   <b-card-group>
     <b-row>
   <b-col md="4"><volunteers-card> </volunteers-card></b-col>
   <b-col md="8"><testimonial-card> </testimonial-card></b-col>
     </b-row>
   </b-card-group>
   <programs-card/>
   </div>
  </div>
</template>

<script>
import AdoptCard from "@/components/AdoptCard";
import VolunteersCard from "@/components/VolunteersCard";
import TestimonialCard from "@/components/TestimonialCard";
import ProgramsCard from "@/components/ProgramsCard";

export default {
  name: 'Home',
  components: {
    AdoptCard,
    VolunteersCard,
    TestimonialCard,
    ProgramsCard
  }
}
</script>

<style lang="scss">


div.card-deck {
  padding-left: 40px;
  padding-right: 40px;
  padding-top: 20px;

}
.margin{
  margin-left: 5%;
  margin-right: 5%;
} 
</style>
