<template>
  <b-container fluid style="margin-top: 60px;">
    <b-row class="m-0 p-0"  >
      <b-col class="m-0 p-0">
        <b-row class="m-0 p-0 background-footer" align-h="center"
          style="background-color: #EEEEEE; height: 228px; padding-top: 19px !important;">
          <b-col sm="12" md="4" class="px-0 find-one-footer remove-padding remove-margin">
            <img
              src="../assets/img/footer/location.svg"
              alt="Location"
              width="27px"
              height="39px"
              class="img-location">
            <span class="first-span">Encontre uma</span><br>
            <span class="second-span">concessionária</span>
          </b-col>

          <b-col sm="12" md="4" class=" remove-padding remove-margin p-0 pt-2 contact-footer">
            <span class="call-center"> CENTRAL DE ATENDIMENTO</span> <br>
            <span class="phone-number">(31)  3123-1234</span>
          </b-col>

          <b-col cols="12" class="m-0 p-0">
            <b-row class="m-0 p-0">
              <b-col class="mb-3 p-0 follow">
                <span>SIGA A BANZAI NAS REDES SOCIAIS</span>
              </b-col>
            </b-row>

            <b-row class="m-0 p-0 " align-h="center">
              <b-col cols="1" class="m-0">
                <div class="background-img-socials rounded-circle">
                  <img class="social-icon-facebook" src="../assets/img/footer/facebook.svg" alt="Image Facebook">
                </div>
              </b-col>

              <b-col cols="1" class="m-0" style="padding-left: 1rem">
                <div class="background-img-socials rounded-circle">
                <b-icon class="social-icon-instagram" icon="instagram" variant="light" scale="1.6"></b-icon>
                </div>
              </b-col>

              <b-col cols="1" class="m-0" style="padding-left: 1rem">
                <div class="background-img-socials rounded-circle">
                  <img class="social-icon-twitter" src="../assets/img/footer/twitter.svg" alt="Image Twitter">
                </div>
              </b-col>
            </b-row>
          </b-col>
        </b-row>

        <b-row class="m-0 final-row-footer" align-h="end" style="padding: 27px 0">
          <b-col sm="12" md="3" class="m-0 pt-2 px-0 text-center footer-logo" >
            <img src="../assets/img/footer/logo@2x.png" alt="Logo"
              width="110px"
              height="28px">
          </b-col>

           <b-col sm="12" md="6 " class="m-0 col-ibama">
              <span class="text-ibama-logo">Todos juntos fazem um trânsito melhor</span>
              <img src="../assets/img/footer/logo_ibama.png" alt="Logo Ibama">
          </b-col>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
.img-location {
  margin-right: 17px;
  margin-left: 20px;
  position: relative;
  top: 0.7rem;
}
.first-span {
  font: normal normal medium 14px/19px Foundry Monoline;
  letter-spacing: 0px;
  width: 85px;
  height: 19px
}

.second-span {
  position: relative;
  left: 3.9rem;
  bottom: 0.9rem;
  font: normal normal 800 22px/30px Foundry Monoline;
  letter-spacing: 0px;
  color: #DF0209;
  width: 180px;
  height: 30px;
  text-transform: uppercase;
}

.find-one-footer {
  text-align: left !important;
  padding-top: 0.5rem !important;
  margin: 0 0 0 -14px;
}

.contact-footer {
  margin: 0 -30px 0 30px;
}

.contact-footer, .find-one-footer {
  width: 270px;
  height: 80px;
  background: #FFFFFF 0% 0% no-repeat padding-box;
  border: 1px solid #DF0209;
  border-radius: 5px;
  text-align: center;
}

.call-center {
  font: italic normal normal 16px/21px Foundry Monoline;
  letter-spacing: -0.7px;
  font-weight: 500;
  color: #727B7A;
}

.phone-number {
  position: relative;
  left: -0.5rem !important;
  font: italic normal normal 26px/35px Foundry Monoline;
  letter-spacing: 0px;
  color: #DF0209;
}

.follow {
  text-align: center;
  font: italic normal normal 24px/32px FoundryMonoline-ExBdIta ☞;
  letter-spacing: 0px;
}

.background-img-socials {
  height: 40px;
  width: 40px;
  background-color: #C5C5C5;
}

.background-img-socials:hover {
  cursor: pointer;
  opacity: 0.9;
  background-color: #707070;
}

.social-icon-facebook {
  position: relative;
  top: 0.4rem;
  left: 0.9rem;
}

.social-icon-instagram {
  position: relative;
  top: 7px;
  left: 12px;
}

.social-icon-twitter {
  position: relative;
  top: 0.4rem;
  left: 0.5rem;
}

.col-1 {
  width: 4.33333333% !important;
}

.col-3 {
  width: 27.333% !important;
}

.text-ibama-logo {
  font: normal normal normal 12.5px/16px Segoe UI;
  letter-spacing: 0px;
  color: #707070;
  margin-right: 18px !important;
}
</style>
