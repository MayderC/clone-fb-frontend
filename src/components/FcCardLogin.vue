<template lang="pug">

form.form__login

  label.form__login_lb(for="id_login_input_email")
    input(id="id_login_input_email" type="text")

  label.form__login_lb(for="id_login_input_pass")
    input(id="id_login_input_pass" type="text")

  fc-buttom(text="Entrar" color="blue").form__login--buttom.form__login--enter

  p ¿Has olvidado tu contraseña?

  fc-buttom(text="Crear cuenta nueva" hexa="#42b72a").form__login--buttom.form__login--register
  
</template>
<script>

import FcButtom from './FcButton.vue'

export default {
  name: 'FcCardLogin',
  components: {FcButtom}
}
</script>

<style lang="sass" scoped>

  .form__login
    display: flex
    flex-direction: column
    padding: 10px
    background-color: #fff
    border-radius: 6px

  .form__login--buttom
    height: 45px
    align-self: flex-start

  .form__login--enter
    width: 100%

  .form__login--register
    width: auto
    padding: 0 0.5em


</style>