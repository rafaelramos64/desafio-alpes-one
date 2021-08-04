<template>
  <b-container fluid>
    <b-row class="emotion-text">
      <b-col>
        <span>A EMOÇÃO DE DIRIGIR LEVA VOCÊ MAIS LONGE</span>
      </b-col>
    </b-row>
    <b-row style="margin-left: 98px; --bs-gutter-x: 0rem;" class="remove-margin">
      <b-col cols="2" class="img-3-cars m-0 p-0">
        <img src="../assets/img/driverEmotion/retangulo16@2x.png" alt="Image Civic"><br>
        <img src="../assets/img/driverEmotion/retangulo19@2x.png" alt="Image Civic"><br>
        <img src="../assets/img/driverEmotion/retangulo21@2x.png" alt="Image Civic"><br>
      </b-col>
      <b-col cols="7" class="img-together m-0 px-0">
        <img class="img-civic" src="../assets/img/driverEmotion/juntosi@2x.png" alt="Image Civic">
        <img class="img-civic-mobile" src="../assets/img/driverEmotion/juntosi.png" height="100px" alt="Image Civic">
      </b-col>
    </b-row>
    <b-row class="civic-text">
      <b-col class="p-0">
        <span>
          O novo Civic Geração 10 traz um design único mudando a categoria de sedãs para sempre.
          Ele garante a melhor dirigibilidade com o máximo em sofisticação e conforto,
          atribuído por seu design interno e diferenciada ergonomia.
        </span>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'DriverEmotion',
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.emotion-text {
  margin: 31px 0 33px 97px;
  font: italic normal normal 34px/46px Foundry Monoline;
  letter-spacing: 0px;
  color: #000000;
}

img {
  width: 165px;
  height: 96px;
  border: 1px solid #D5D5D5;
  margin-bottom: 5px;
  object-fit: cover;
}

.img-civic {
  width: 680px;
  height: 212px;
  border: none !important;
}

.img-together {
  padding-top: 63px ;
}

.civic-text {
  margin: 38.29px 0 53px 95px;
  width: 870px;
  height: 63px;
  font: normal normal normal 18px/24px Foundry Monoline;
  letter-spacing: 0px;
}

</style>
