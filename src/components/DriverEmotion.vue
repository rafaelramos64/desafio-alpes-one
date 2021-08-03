<template>
  <b-container fluid>
    <b-row class="emotion-text">
      <b-col>
        <span>A EMOÇÃO DE DIRIGIR LEVA VOCÊ MAIS LONGE</span>
      </b-col>
    </b-row>
    <b-row style="margin-left: 98px !important">
      <b-col cols="2">
        <img src="../assets/img/driverEmotion/retangulo16@2x.png" alt="Image Civic"><br>
        <img src="../assets/img/driverEmotion/retangulo19@2x.png" alt="Image Civic"><br>
        <img src="../assets/img/driverEmotion/retangulo21@2x.png" alt="Image Civic"><br>
      </b-col>
      <b-col cols="7" class="img-together">
        <img src="../assets/img/driverEmotion/juntosi@2x.png" alt="Image Civic"><br>
      </b-col>
    </b-row>
    <b-row class="civic-text" style="">
      <b-col>
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
/* Reset rows and cols */
.row, .col {
  padding: 0px !important;
  margin: 0px !important;
}

.row > * {
  padding: 0px !important;
  margin: 0px !important;
}

.emotion-text {
  margin: 31px 0 33px 97px !important;
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

.img-together > img {
  width: 680px;
  height: 212px;
  border: none !important;
}

.img-together {
  /* margin-left: 40px !important; */
  padding-top: 63px !important;
}

.civic-text {
  margin-top: 38.29px !important;
  margin-left: 95px !important;
  margin-bottom: 53px!important;
  width: 870px;
  height: 63px;
  font: normal normal normal 18px/24px Foundry Monoline;
  letter-spacing: 0px;
}
</style>
