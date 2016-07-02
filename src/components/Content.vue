<template>
  <div class="container content_box">
    <app-carousel></app-carousel>
    <app-news></app-news>
    <app-info></app-info>
    <app-service></app-service>
    <app-us></app-us>
  </div>

</template>
<style>
  .content_box {
    margin-top: 16px;
  }

</style>
<script>
  import Carousel from './pages/Carousel.vue';
  import News from './pages/News.vue';
  import Info from './pages/Info.vue';
  import Service from './pages/Service.vue';
  import Us from './pages/Us.vue';

  export default{
        data(){
            return{
                msg:'hello vue'
            }
        },
        components:{
          'app-carousel': Carousel,
          'app-news': News,
          'app-info': Info,
          'app-service': Service,
          'app-us': Us

        }
    }
</script>
