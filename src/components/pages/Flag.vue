<style>

  .hot_flag {
    position: absolute;
    right: -32px;
    top: -10px;
    margin-left: 6px;
  }

  .flag_box {
    width: 30px;
    height: 18px;
    border-radius: 2px;
    line-height: 18px;
    text-align: center;
    background-color: #ff3b1b;
  }
  .flag_box span {
    color: #fff;
    font-size: 13px;
  }

  .triangle {
    position: absolute;
    left: 8px;
    width: 0;
    height: 0;
    border-right: 10px solid transparent;
    border-top: 8px solid #ff3b1b;
    z-index: 80;
  }
  .transparent {
    position: absolute;
    left: 7px;
    width: 0;
    height: 0;
    border-right: 4px solid transparent;
    border-top: 10px solid #fff;
    z-index: 100;
  }


</style>
<template>
    <div class="hot_flag">
        <div class="flag_box">
          <span>NEW</span>
        </div>
        <div class="transparent"></div>
        <div class="triangle"></div>
      </div>
</template>

<script>
    export default{
        data(){
            return{
                msg:'hello vue'
            }
        }
    }
</script>
