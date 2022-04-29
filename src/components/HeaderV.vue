<template>
  <div class="container-fluid bg-jumbotron ">
      <div class="container-fluid py-5 d-flex justify-content-between align-items-center super-marginbt">
         <div class="row">
           <a href="#"><img src="../assets/img/avada-music-logo.png" class="margin-0" alt=""></a>
         </div>
         <div class="row">
           <a href="#"><img src="../assets/img/iconmonstr-menu-thin-240.png" class="invert-cl size-menu margin-1" alt=""></a>
         </div>
      </div>
      <div class="container-sm py-5 mt-5 d-flex justify-content-center align-items-center flex-column ">
        <div class="row py-2">
          <h1 class="text-white disp0 fw-bold">Untold Stories</h1>
        </div>
        <div class="row py-2">
          <h4 class="text-white fst-italic">There is an untold stories behind every favorite song.</h4>
        </div>
        <div class="row flex-row pb-5 super-marginbt">
          <div class="col py-5">
            <button class="text-uppercase mx-2 p-2 px-4 border-cl-mandy bg-cl-mandy">latest album</button>
            <button class="text-uppercase mx-2 p-2 border border-light text-white">live dates</button>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderV',
 
}
</script>


<style scoped lang="scss">

@import '../assets/style/index.scss';

.bg-jumbotron{
    background-image: url('../assets/img/home_slider.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

</style>
