 <template>
  <b-card no-body>
    <b-tabs card>
      <b-tab title="PROGRAMS" active>
        <b-card title="BEHAVIOR PROGRAM">
          <b-row>
            <b-col md="2">
              <b-card-img
                :src="require('../assets/img/friend-in-trouble.png')"
                img-alt="Dog image"
                img-left
              />
            </b-col>
            <b-col md="6">
              <b-card-text>Evaluation of each dog using specialists who deteremine the best training that will help your frind to be a better family member.</b-card-text>
              <b-button variant="outline-info">READ MORE</b-button>
            </b-col>
          </b-row>
        </b-card>
        <b-card title="MY NEXT FAMILY">
          <b-row>
            <b-col md="2">
              <b-card-img
                :src="require('../assets/img/friend-in-trouble.png')"
                img-alt="Dog image"
                img-left
              />
            </b-col>
            <b-col md="6">
              <b-card-text>Are you looking for a new family member? Then, this program is for you. Don't buy, adopt here, and let's give a home to these amazing friends.</b-card-text>
              <b-button variant="outline-info">READ MORE</b-button>
            </b-col>
          </b-row>
        </b-card>
      </b-tab>
      <b-tab title="ASSOCIATED COMPANIES">
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
      <style lang="stylus" scoped></style>
