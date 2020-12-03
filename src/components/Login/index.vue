<template>
  <div class="login_body">
    <div>
      <input class="login_text" type="text" placeholder="账户名/手机号/Emall">
    </div>
    <div>
      <input class="login_text" type="text" placeholder="请输入密码">
    </div>
    <div>
      <input class="login_submit" type="submit" value="登录">
    </div>
    <div>
      <a href="#">立即注册</a>
      <a href="#">找回密码</a>
    </div>
  </div>
</template>

<script>
export default {
  name:'Login'
}
</script>

<style>
  .login_body{
    flex: 1;
    overflow: auto;
    margin-top: 51px;
  }
  .login_body .login_text{
    width: 100%;
    height: 30px;
    font-size: 12px;
    margin-bottom: 3px;
    border:none ;
    background-color: rgb(184, 184, 110)
    ;
  }
  .login_body .login_submit{
    width: 100%;
    background-color: brown;
    border:none ;
    height: 50px;
    font-size: 20px;
  }
  .login_body a{
    color: red;
    text-decoration: none;
  }
  .login_body a:nth-child(2){
    float: right;

  }
</style>