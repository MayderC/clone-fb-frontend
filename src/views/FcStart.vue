<template lang="pug">
  
main.main__start
  section.start__login
    section.start__login__item.start__login_item--logo
      div.start__logo
        <!--img(src="../assets/img/frontend.svg", alt="alt")-->
        p facebook
      div.start__description
        p Clon del login y home de facebook (frontend), No esta conectado a ningun servidor.
    section.start__login__item.start__login_item--form
      div.start__card-login
        fc-card-login



</template>


<script>
import FcCardLogin from '../components/FcCardLogin.vue'
export default {
  name: 'FcStart',
  components : {
    FcCardLogin
  }
}
</script>
