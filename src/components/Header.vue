<style>
  header {
    position: relative;
    height: 180px;
  }

  header > img:nth-of-type(1) {
    position: absolute;
    width: 1200px;
    height: 180px;
    left: 0;
    top: 0;
    z-index: -1;
  }

  header > img:nth-of-type(2) {

    margin-top: 48px;
    margin-left: 20px;
  }

  .login {
    float: right;
    margin-top: 28px;
  }

  .sign-in {
    padding-right: 10px;
    border-right: 1px solid #000;
    font-size: 20px;
    color: #000;
    cursor: pointer;
  }

  .sign-up {
    margin-left: 8px;
    margin-right: 68px;
    font-size: 20px;
    color: #000;
    cursor: pointer;
  }

  .sign-in:hover, .sign-up:hover {
    color: #ff9a5f;
  }


  .input-group {
    position: absolute;
    width: 418px;
    height: 42px;
    right: 100px;
    bottom: 20px;
    background-color: #eee;
  }

  .input-group input:focus {
    outline: none;
  }

  .input-outline {
    padding: 4px;
  }

  .input-outline > input {
    border: none;
  }

  .btn {
    width: 116px;
    border: none;
    border-radius: 0;
    background-color: #eee;
  }

  .btn:focus {
    outline: none;
  }


</style>
<template>
  <header>
    <img src="../assets/header.png" alt="logo">


    <div class="login">
      <span class="sign-in">注册</span>
      <span class="sign-up">登录</span>
    </div>

    <img src="../assets/logo.png" alt="logo">

    <div class="input-group">
      <div class="input-outline">
        <input type="text" class="form-control" placeholder="请输入关键字">
      </div>
      <span class="input-group-btn">
        <button class="btn btn-default" type="button">搜索</button>
      </span>
    </div>
  </header>
</template>
<script>
  export default{
    data () {
      return {}
    }
  }
</script>
