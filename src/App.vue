<style>
  body, table, tr, th, td, form, input, ul, li, div, a, h2, p{
    margin: 0;
    padding: 0;
  }
  .container {
    width: 1200px;
    padding: 0;
    position: relative;
  }
  .line {
    width: 100%;
    height: 4px;
    background-color: #ff9a5f;
  }
</style>
<template>
  <div class="container">
    <app-header></app-header>
    <div class="line"></div>
    <app-navigation></app-navigation>
    <app-content></app-content>
    <app-footer></app-footer>
  </div>
</template>
<script>
  import Header from './components/Header.vue'
  import Navigation from './components/Navigation.vue'
  import Content from './components/Content.vue'
  import Footer from './components/Footer.vue'

  export default{
    name: 'Container',
    data(){
      return{
        msg:'hello vue'
      }
    },
    components:{
      'app-header': Header,
      'app-navigation': Navigation,
      'app-content': Content,
      'app-footer': Footer
    }
  }
</script>
