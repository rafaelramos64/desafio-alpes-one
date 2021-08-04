<template>
  <b-container fluid>
    <b-row
      align-h="between"
      no-gutters
      style="padding: 18px 114px; max-width: 100%; --bs-gutter-x: 0rem;" class=" ">
      <b-col md="6" sm="12" class="p-0 center-contact-logo">
        <img src="../assets/img/header/logo.png" alt="Logo">
      </b-col>

      <b-col md="6" sm="12" style="text-align: right" class="p-0 center-contact-logo">
        <span class="call-center"> CENTRAL DE ATENDIMENTO</span> <br>
        <span class="phone-number">(31) 3123-1234</span>
      </b-col>
    </b-row>

    <b-row>
      <b-col>
        <b-img fluid :src="require('../assets/img/header/retangulo1.png')" alt="Img Civic" class="background-civic"> </b-img>
        <div class="civic-10">
          <b-img fluid :src="require('../assets/img/header/civic_solo.png')" alt="Img Civic"> </b-img>
          <b-img fluid :src="require('../assets/img/header/civic_10.svg')" alt="Img Civic"> </b-img>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'Header',
  data () {
    return {
    }
  }
}
</script>

<style scoped lang="scss">
.call-center {
  font: italic normal normal 16px/21px Foundry Monoline;
  letter-spacing: -0.7px;
  color: #727B7A;
}

.phone-number {
  position: relative;
  left: -0.9rem !important;
  font: italic normal normal 26px/35px Foundry Monoline;
  letter-spacing: 0px;
  color: #DF0209;
}

.col, .row {
  padding: 0 !important;
  margin: 0 !important;
}
</style>"
