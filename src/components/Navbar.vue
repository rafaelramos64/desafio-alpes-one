<template>
  <b-container fluid>
    <b-row
      class="initial-bar m-0"
      no-gutters>
      <b-col cols="6" class="m-0 p-0">
        <img class="nav-icons remove-padding remove-margin" src="../assets/img/navbar/home-button.svg" alt="Home">
        <span class="inicial-bar-text"> Ir para o Portal Banzai</span>
      </b-col>

      <b-col cols="6" class="m-0 p-0">
        <b-row no-gutters align-h="end">
          <b-col cols="4" class="m-0 p-0 remove-padding remove-margin">
            <img class="nav-icons remove-padding remove-margin" src="../assets/img/navbar/location.svg" alt="Location">
            <span class="inicial-bar-text"> Encontre uma concessionária</span>
          </b-col>

          <b-col cols="3" class="m-0 pl-0 pr-2 remove-padding remove-margin" style="text-align: right;">
            <img class="nav-icons remove-margin" src="../assets/img/navbar/black-envelope.svg" alt="Email">
            <span class="inicial-bar-text">Fale Conosco</span>
          </b-col>
        </b-row>
      </b-col>
    </b-row>

    <b-row
      align-h="center"
      class="initial-bar-mobile pt-1">
      <b-col cols="1" style="margin-right: 0">
        <img class="home-icon" src="../assets/img/navbar/home-button.svg" alt="Home">
      </b-col>

      <b-col cols="1" class="">
        <img class="location-icon" src="../assets/img/navbar/location.svg" alt="Location">
      </b-col>

      <b-col cols="1" style="margin-left: 0;">
        <img class="email-icon" src="../assets/img/navbar/black-envelope.svg" alt="Email">
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'Navbar'
}
</script>

<style lan="scss" scoped >
.initial-bar {
  background-color: #EEEEEE;
  background-repeat: no-repeat;
  background-origin: padding-box;
  width: 100%;
  height: 25px;
  padding: 0 114px !important;
}

.nav-icons {
  position: relative;
  top: -2px;
  width: 20px;
  height: 17px;
  margin-right: 4px;
  border: none !important;
}

.inicial-bar-text {
  width: 116px;
  height: 16px;
  text-align: left;
  font: 12px/16px Foundry Monoline;
  letter-spacing: 0px;
  color: #707070;
  opacity: 1;
}

.inicial-bar-text:hover, .home-icon:hover, .location-icon:hover, .email-icon:hover {
  cursor: pointer;
  opacity: 0.8;
}

</style>
