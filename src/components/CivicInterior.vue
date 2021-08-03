<template>
  <b-container fluid>
    <b-row class="p-0 m-0" no-gutters>
      <b-col class="p-0 m-0">
        <img class="civic-interior" src="../assets/img/civicInterior/grupo74@2x.png" alt="Civic Interior image">
      </b-col>
    </b-row>

    <b-row class="p-0 m-0 ready">
      <b-col class="p-0 m-0 ">
        <span>PRONTO PARA TER UM HONDA?</span>
      </b-col>
    </b-row>

    <b-row class="p-0 m-0  know">
      <b-col class="p-0 m-0">
        <span>Conheça os últimos grandes lançamentos da honda.</span>
      </b-col>
    </b-row>

    <b-row style="margin-left: 98px !important" class="p-0 m-0">
      <b-col cols="3" class="p-0 m-0">
        <img class="cars-exemples" src="../assets/img/civicInterior/accord.png" alt="Image Civic">
      </b-col>
      <b-col cols="3" class="p-0 m-0">
        <img class="cars-exemples" src="../assets/img/civicInterior/city.png" alt="Image Civic">
      </b-col>
      <b-col cols="3" class="p-0 m-0">
        <img class="cars-exemples" src="../assets/img/civicInterior/fit_2018.png" alt="Image Civic">
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'CivicInterior',
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.civic-interior {
  height: 807px;
  max-width: 100%;
  margin-bottom: 60px;
}

.ready {
  /* margin-top: 38.29px !important;
  margin-bottom: 53px!important; */
  margin-left: 95px !important;
  width: 495px;
  height: 46px;
  font: italic normal normal 34px/46px Foundry Monoline;
}

.know {
  margin-bottom: 33px!important;
  font: normal normal normal 18px/24px Foundry Monoline;
  width: 414px;
  height: 24px;
  margin-left: 95px !important;
}

.cars-exemples {
  width: 211px;
  height: 179px
}

/* .row, .col {
  padding: 0px;
  margin: 0px;
} */
</style>
