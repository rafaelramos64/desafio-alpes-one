<template>
  <b-container fluid>
    <b-row
      class="initial-bar m-0"
      no-gutters>
      <b-col cols="6" class="m-0 p-0">
        <img class="nav-icons" src="../assets/img/navbar/home-button.svg" alt="Home">
        <span class="inicial-bar-text"> Ir para o Portal Banzai</span>
      </b-col>

      <b-col cols="6" class="m-0 p-0">
        <b-row no-gutters align-h="end">
          <b-col cols="4" class="m-0 p-0">
            <img class="nav-icons" src="../assets/img/navbar/location.svg" alt="Location">
            <span class="inicial-bar-text"> Encontre uma concessionária</span>
          </b-col>

          <b-col cols="3" class="m-0 pl-0 pr-2" style="text-align: right;">
            <img class="nav-icons" src="../assets/img/navbar/black-envelope.svg" alt="Email">
            <span class="inicial-bar-text">Fale Conosco</span>
          </b-col>
        </b-row>
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

/* Media queries for responsive mobile */

@media only screen and (max-width: 500px) {
  .initial-bar {
    min-width: 100%;
    height: 40px;
    padding: 0 !important;
  }

  .inicial-bar-text{
    display: none !important;
  }
}

</style>
