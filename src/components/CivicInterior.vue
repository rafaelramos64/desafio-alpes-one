<template>
  <b-container fluid>
    <b-row class="p-0 m-0" no-gutters>
      <b-col class="p-0 m-0">
        <img class="civic-interior" src="../assets/img/civicInterior/grupo74@2x.png" alt="Civic Interior image">
      </b-col>
    </b-row>

    <b-row class="p-0 ready remove-margin">
      <b-col class="p-0 m-0 ">
        <span>PRONTO PARA TER UM HONDA?</span>
      </b-col>
    </b-row>

    <b-row class="p-0 know remove-margin ">
      <b-col class="p-0 m-0">
        <span>Conheça os últimos grandes lançamentos da honda.</span>
      </b-col>
    </b-row>

    <b-row style="margin-left: 98px !important" class="p-0 m-0">
      <b-col cols="3" class="p-0 m-0 card-exemples">
        <img class="cars-exemples" src="../assets/img/civicInterior/accord.png" alt="Image Civic">
        <span class="car-exemple-text">
          Novo Honda Accord: a combinação perfeita de três atributos exigidos pelo consumidor:
          elegância, luxo e alto desempenho.
        </span>
        <button class="know-button">CONHEÇA MAIS</button>
      </b-col>

      <b-col cols="3" class="p-0 m-0 card-exemples">
        <img class="cars-exemples" src="../assets/img/civicInterior/city.png" alt="Image Civic">
        <span class="car-exemple-text">
          O City está muito mais moderno e esportivo. Com design único
          e mais tecnológico do que nunca, ele vai conquistar todos os olhares.
        </span>
        <button class="know-button">CONHEÇA MAIS</button>
      </b-col>

      <b-col cols="3" class="p-0 m-0 card-exemples">
        <img class="cars-exemples" src="../assets/img/civicInterior/fit_2018.png" alt="Image Civic">
        <span class="car-exemple-text">
          Com seu design inconfundível, o novo Honda Fit traz novidades
          que vão surpreender a todos e atrair ainda mais fãs.
        </span>
        <button class="know-button">CONHEÇA MAIS</button>
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
  margin-left: 95px;
  width: 495px;
  height: 46px;
  font: italic normal bold 34px/46px Foundry Monoline;
  letter-spacing: 0px;
}

.know {
  margin-left: 95px;
  margin-bottom: 33px;
  font: normal normal bold 17px/24px Foundry Monoline, "Regular";
  width: 414px;
  height: 24px;
  letter-spacing: 0px;
}

.card-exemples {
  width: 270px;
  height: 350px;
  background: #FFFFFF 0% 0% no-repeat padding-box;
  border: 1px solid #D5D5D5;
  opacity: 1;
  margin-right: 30px !important;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}

.cars-exemples {
  width: 211px;
  height: 179px;
  margin-top: 4px;
}

.car-exemple-text {
  width: 230px;
  height: 79px;
  text-align: center;
  font: normal normal 300 14.4px/19px Foundry Monoline;
  letter-spacing: 0px;
  margin-bottom: 20px;
  margin-top: 10px;
}

.know-button {
  background-color: transparent;
  width: 230px;
  height: 36px;
  border: 1px solid #D5D5D5;
  border-radius: 4px !important;
  font: normal normal 300 14px/24px "Roboto", sans-serif;
  letter-spacing: 0px;
  color: #000000;
  margin: 0 auto;
  margin-bottom: 22px;
}

.know-button:hover {
  background-color: #1CB72A;
  color: #fff;
  font-weight: bold;
}
</style>
