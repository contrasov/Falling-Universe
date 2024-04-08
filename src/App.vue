<template>
  <div class="landing-app"> 
    <HeaderNav/>
    <BannerHome/>
    <LasNewsDiv/>
    <ContainerFeed/>
    <FooterCredits/>
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav.vue'
import BannerHome from './components/BannerHome.vue'
import LasNewsDiv from './components/LasNewsDiv.vue'
import ContainerFeed from './components/ContainerFeed.vue'
import FooterCredits from './components/FooterCredits.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    BannerHome,
    LasNewsDiv,
    ContainerFeed,
    FooterCredits
  }
}

</script>

<style>  /*não vou alterar n*/
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background-image: url('./assets/background-2.svg');
  background-repeat: no-repeat;
  background-size: cover;
}

.landing-app {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 24px;
}
</style>
