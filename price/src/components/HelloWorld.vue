<template>
  <div class="hello">
    <el-container>
      <el-main>
             <div id="loginBox">
                 <div id="login">
                     <div><span> 账号：</span><input type="text" ></div>
                     <div><span> 密码：</span><input type="text"></div>
                     <div><el-checkbox v-model="checked">记住密码</el-checkbox></div>
                     <div id="button">登录</div>
                 </div>
                

             </div>

      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
       checked: true
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.el-main {
  background-color: #21272F;
  text-align: center;
  height: 1060px;
  width: 1600px;
  display: flex;
  justify-content: center;
  align-items: center;
}
#loginBox{
     width:700px ;
     height: 400px;
     background: #F2F2F2;
     border-radius: 10px;
     display: flex;
     justify-content: center;
}

input{
  height: 51px;
  width: 505px;
}
 #login>div:nth-of-type(1){
  margin-top: 62px;
  margin-bottom: 20px;
}
#login>div:nth-of-type(3) {
   height: 51px;
   width: 505px;
   display: flex;
   justify-content: flex-end;
   align-items: center;
}
  #login{
     color: #9B9B9B;
     width: 606PX;
     
  }
  #button{
    width: 500px;
    height: 64px;
    background: #FF4D4D;
    border-radius: 32px;
    color:white;
    display: flex;
    align-items: center;
    justify-content: center;
  }

</style>
