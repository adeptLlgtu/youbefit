<template>
  <div class="container">
    <img class="container-background__desktop" :src="backgroundDesktop" alt="">
    <img class="container-background__phone" :src="backgroundPhone" alt="">
    <img class="logo" :src="logo" alt="">
    <a class="light-start" href="/">
      <img :src="lightStart" alt="">
    </a>
    <a class="fitness" href="/">
      <img :src="fitness" alt="">
    </a>
    <a class="question" href="/">
      <p>Задать вопрос</p>
      <img :src="telegram" alt="">
    </a>
  </div>
</template>

<script>
import backgroundDesktop from '../assets/background-desktop.svg'
import backgroundPhone from '../assets/background-phone.svg'
import fitness from '../assets/fitnes.svg'
import lightStart from '../assets/light-start.svg'
import logo from '../assets/logo.svg'
import telegram from '../assets/telegram.svg'

export default {
  name: "Home",
  data(){
    return{
      backgroundDesktop, backgroundPhone, fitness, lightStart, logo, telegram
    }
  }
}
</script>

