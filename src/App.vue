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
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

</style>
