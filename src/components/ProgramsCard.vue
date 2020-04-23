 <template>
  <b-card no-body id="tabs-card">
    <b-tabs pills>
      <b-tab title="PROGRAMS" active :title-link-class="'mytab'"> 
        <b-card>
          <b-row>
            <b-col md="2">
              <b-card-img
                :src="require('../assets/img/friend-in-trouble.png')"
                img-alt="Dog image"
                img-left
              />
            </b-col>
            <b-col md="6">
              <b-card-title>BEHAVIOR PROGRAM</b-card-title>
              <b-card-text>Evaluation of each dog using specialists who deteremine the best training that will help your frind to be a better family member.</b-card-text>
              <b-button variant="outline-info">READ MORE</b-button>
            </b-col>
          </b-row>
        </b-card>
        <b-card>
          <b-row>
            <b-col md="2">
              <b-card-img
                :src="require('../assets/img/friend-in-trouble.png')"
                img-alt="Dog image"
                img-left
              />
            </b-col>
            <b-col md="6">
              <b-card-title>MY NEXT FAMILY</b-card-title>
              <b-card-text>Are you looking for a new family member? Then, this program is for you. Don't buy, adopt here, and let's give a home to these amazing friends.</b-card-text>
              <b-button variant="outline-info">READ MORE</b-button>
            </b-col>
          </b-row>
        </b-card>
      </b-tab>
      <b-tab title="ASSOCIATED COMPANIES" lazy :title-item-class="'mytab'">
        <b-card-text>Tab contents 2</b-card-text>
      </b-tab>
    </b-tabs>
  </b-card>
</template>

  <script>
export default {
  name: "programs-card"
};
</script>
      <style scoped>
.card-body {
  padding: 0;
}
div.card-header {
  padding: 0% 0%;
  background-image: none;
  background-color: #ffffff !important;
}
.card {
  border-style: none;
}
.row {
    padding-bottom: 1%;
    padding-top: 1%;
}
#tabs-card {
    padding-top: 1%
}
/* .nav-pills .nav-link.active {
    color: #322982;
    border-bottom: solid #322982;
    background-color: white !important;
} */
/* .mytab{
    color: #FF0000 !important;
} */
ul.nav > li.nav-item > a.nav-link {
    background-color: white !important;
}
</style>
