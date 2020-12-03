<template>
  <div class="movie_body">
    <ul>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_1.jpg" alt=""></div>
        <div class="info_list">
          <h2>无名之辈</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：陈建斌，任素夕,潘斌龙</p>
          <p>今天55家影院放映607场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_2.jpg" alt=""></div>
        <div class="info_list">
          <h2>毒液：致命守护</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：汤姆·哈迪,米歇尔·威廉姆斯,里斯·阿迈德</p>
          <p>今天56家影院放映417场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_1.jpg" alt=""></div>
        <div class="info_list">
          <h2>无名之辈</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：陈建斌，任素夕,潘斌龙</p>
          <p>今天55家影院放映607场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_2.jpg" alt=""></div>
        <div class="info_list">
          <h2>毒液：致命守护</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：汤姆·哈迪,米歇尔·威廉姆斯,里斯·阿迈德</p>
          <p>今天56家影院放映417场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_1.jpg" alt=""></div>
        <div class="info_list">
          <h2>无名之辈</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：陈建斌，任素夕,潘斌龙</p>
          <p>今天55家影院放映607场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
      <li>
        <div class="pic_show"><img src="../../../public/images/movie_2.jpg" alt=""></div>
        <div class="info_list">
          <h2>毒液：致命守护</h2>
          <p>观众评<span class="grade">9.2</span></p>
          <p>主演：汤姆·哈迪,米歇尔·威廉姆斯,里斯·阿迈德</p>
          <p>今天56家影院放映417场</p>
        </div>
        <div class="btn_mall">
          购票
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name:'NowPlaying'
}
</script>

<style scoped>
.movie_body{
flex: 1;
overflow: auto;
}
ul{
  margin: 0 12px;
  overflow: hidden;
}
li{
  width: 100%;
  height: 100px;
  display: flex;
  margin-left: 5px;
  border-bottom: 1px solid #ccc;
  margin-top: 12px;
}
li .pic_show img{
  width: 50px;
  height: 90px;
}
li .info_list{
  margin-left: 10px;
  height: 100%;
}
li .info_list h2{
  font-size: 17px;
}
li .info_list p{
  overflow: hidden;
  font-size: 13px;
  line-height: 22px;
  width: 200px;
  color: #666;
  white-space: nowrap;
  text-overflow: ellipsis;
}
li .info_list p .grade{
  font-weight: 600px;
  color: #faaf00;
  font-size: 15px;
}
li .btn_mall ,.btn_pre{
  width: 47px;
  height: 27px;
  background-color: red;
  border-radius: 5px;
  line-height: 27px;
  text-align: center;
  margin-top: 28px;
  margin-right: 12px;
  cursor: pointer;
}
li .btn_pre{
  background-color: rgb(87, 87, 223);
}

</style>
