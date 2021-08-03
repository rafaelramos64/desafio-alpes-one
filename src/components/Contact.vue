<template>
  <b-container>
    <b-row>
      <b-col>
        <div class="contact-card">
          <b-row align-h="start" style="margin-bottom: 5px !important;">
            <b-col cols="2">
              <img src="../assets/img/contact/grupo45.svg" alt="Call icon">
            </b-col>
            <b-col cols="6" class="contact-request">
             <span> Solicitar um</span> <br>
             <span>CONTATO</span>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-form @submit.stop.prevent="testForm()">
                <b-form-group>
                  <b-input-group-prepend class="form-icons"><img src="../assets/img/contact/grupo32.svg" alt=""></b-input-group-prepend>
                  <b-form-input
                    type="text"
                    placeholder="Nome"
                    autocomplete="off"
                    required>
                  </b-form-input>
                </b-form-group>

                <b-form-group>
                  <b-input-group-prepend class="form-icons"> <img src="../assets/img/contact/black-envelope.svg" alt=""> </b-input-group-prepend>
                  <b-form-input
                    type="email"
                    placeholder="E-mail"
                    autocomplete="off"
                    required>
                  </b-form-input>
                </b-form-group>

                <b-form-group>
                  <b-input-group-prepend class="form-icons"> <img src="../assets/img/contact/call-answer.svg" alt=""> </b-input-group-prepend>
                  <b-form-input
                    type="text"
                    placeholder="Telefone"
                    autocomplete="off"
                    required>
                  </b-form-input>
                </b-form-group>

                <b-form-group>
                  <b-input-group-prepend class="form-icons"> <img src="../assets/img/contact/clock.svg" alt=""> </b-input-group-prepend>
                  <b-form-input
                    list="hour"
                    placeholder="Escolha o horário"
                    required>
                  </b-form-input>

                  <datalist id="hour">
                    <option disabled value="dd">Horários</option>
                    <option v-for="hour in hours" :key="hour" :value="hour">{{ hour }}</option>
                  </datalist>
                </b-form-group>

                <b-form-group>
                  <b-input-group-prepend class="form-icons"> <img src="../assets/img/contact/location.svg" alt=""> </b-input-group-prepend>
                  <b-form-input
                    list="unity"
                    placeholder="Escolha a unidade"
                    required>
                  </b-form-input>

                  <datalist id="unity">
                    <option disabled value=" dd">Unidades</option>
                    <option v-for="unity in unities" :key="unity" :value="unity">{{ unity }}</option>
                  </datalist>
                </b-form-group>

                <button type="submit" class="confirm-button">AGENDAR TEST DRIVE</button>
              </b-form>
            </b-col>
          </b-row>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      hours: ['10:00', '12:00', '14:00', '16:00'],
      unities: ['Sussuapara-PI', 'Picos-PI', 'São luiz do Piau-PI', 'Bocaina-PI']
    }
  },

  methods: {
    testForm () {
      console.log('Ok, Agendado!')
    }
  }
}
</script>

<style lang="scss" scoped>
.contact-card {
  position: fixed;
  top: 200px;
  left: 995px;
  width: 270px;
  height: 352px;
  background: #EEEEEE no-repeat padding-box;
  box-shadow: 0px 0px 5px #00000029;
  border-radius: 4px;
  opacity: 1;
  padding: 19px 20px 20px 19px;
}

.contact-request {
  position: relative;
  top: -0.4rem;
  left: 0.7rem;
}

/* Reset rows and cols */
.row, .col {
  padding: 0px !important;
  margin: 0px !important;
}

.row > * {
  padding: 0px !important;
  margin: 0px !important;
}

span:first-of-type {
  font: normal normal medium 14px/19px Foundry Monoline;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
}

span:last-of-type {
  font: normal normal 800 22px/30px Foundry Monoline;
  letter-spacing: 0px;
  color: #DF0209;
  position: relative;
  top: -0.3rem
}

/* Aqui, foi aplicada uma pequena alteração na borda do input devido um conflito com as opacidades do background
e da borda com a da cor da font */
.form-control {
  width: 100% !important;
  height: 36px !important;
  background-color: transparent !important;
  font: normal normal normal 14px/24px 'Roboto', sans-serif;
  letter-spacing: 0px;
  color: #00000061;
  background: #FFFFFF no-repeat padding-box;
  border: 1.5px solid #D5D5D5;
  border-radius: 4px !important;
  opacity: 1;
  padding-left: 2.2rem;
}

.form-control:focus {
  box-shadow: none !important;
  border-color: #1CB72A !important;
}

.confirm-button {
  background: #1CB72A 0% 0% no-repeat padding-box;
  border-radius: 4px;
  opacity: 1;
  width: 230px;
  height: 45px;
  font: normal normal bold 14px/24px 'Roboto', sans-serif;
  letter-spacing: 0px;
  color: #FFFFFF;
  opacity: 1;
  border: none !important;
  box-shadow:none !important;
}

.confirm-button:hover {
  opacity: 0.9;
}

/* Posicioning form icons dua to a fault on bootstrapvue */
.form-group {
  /* height: 36px !important; */
  position: relative;
  margin-bottom: 5px;
}

.form-icons {
  position: absolute;
  top: 0.2rem;
  left: 11px;
}
</style>
