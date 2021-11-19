<template lang="pug">


span(:class="[ 'fc_buttom' , color ]" :style="{ backgroundColor: hexa }") {{text}}


</template>

<script>
export default {
  name: 'FcButtom',
  props : {
    text : {type : String, default : ''},
    color : {type: String, default : ''},
    hexa: {type: String, default : ''}
  }
}
</script>

<style lang="sass" scoped>

  .fc_buttom
    font-family: SFProDisplay-Regular, Helvetica, Arial, sans-serif
    font-size: 1.5em
    font-weight: normal
    color : #fff
    border-radius: 6px
    display: grid
    place-items: center

  .blue
    background-color: #1877F2


</style>