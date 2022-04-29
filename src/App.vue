<template>
  <div id="app">
 <HeaderV/>
 <MainV/>
 <FooterV/>
  </div>
</template>

<script>
import "bootstrap"
import HeaderV from './components/HeaderV.vue'
import MainV from './components/MainV.vue'
import FooterV from './components/FooterV.vue'

export default {
  name: 'App',
  components: {
    HeaderV,
    MainV,
    FooterV
  }
}
</script>

<style lang="scss">

@import "bootstrap/dist/css/bootstrap.min.css";
@import './assets/style/index.scss';

</style>
