<template>
  <div class="search_body">
    <div class="search_input">
      <div class="search_input_wrapper">
        <i class="iconfont icon-sousuo"></i>
        <input type="text">
      </div>
    </div>
    <div class="search_result">
      <h3>电影/电视剧/综艺</h3>
      <ul>
        <li>
          <div class="img"><img src="../../../public/images/movie_1.jpg" alt=""></div>
          <div class="info">
            <p><span>无名之辈</span><span>8.6</span></p>
            <p>A Cool Fish</p>
            <p>剧情，戏剧，犯罪</p>
            <p>2020-12-15</p>
          </div>
        </li>
        <li>
          <div class="img"><img src="../../../public/images/movie_1.jpg" alt=""></div>
          <div class="info">
            <p><span>无名之辈</span><span>8.6</span></p>
            <p>A Cool Fish</p>
            <p>剧情，戏剧，犯罪</p>
            <p>2020-12-15</p>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name:'Search'
}
</script>

<style>
  .search_body{
    flex: 1;
    overflow: auto;
}
  .search_input{
    background-color: #f5f5f5;
    padding: 8px 10px;
    border: 1px solid #e5e5e5;
  }
  .search_input_wrapper{
    background-color: #fff;
    border: 1px solid #e6e6e6;
    padding: 0px 10px;
    
  }
  .search_input_wrapper i{
    padding: 4px 0;
    font-size: 16px;
  }
  .search_input_wrapper input{
    border: none;
    font-size: 12px;
    color: #333;
    padding: 4px 0;
    outline: none;
    margin-left: 5px;
  }
  .search_result h3{
    font-size: 16px;
    padding: 8px 10px;
    border: 1px solid #ccc;
    color: #333;
  }
  .search_result li{
    border-bottom: 1px dashed #c9c9c9;
    padding: 9px 15px;
    box-sizing: border-box;
    display: flex;
  }
  .search_result img{
    width: 60px;
    float: left;
  }
  .search_result .info{
    float: left;
    margin-left: 15px;
  }
  .search_result .info p{
    height: 22px;
    display: flex;
    line-height: 22px;
    font-size: 12px;
  }
  .search_result .info p:nth-child(1) span:nth-child(1){
    font-size: 18px;
  }
  .search_result .info p:nth-child(1) span:nth-child(2){
    font-size: 16px;
    color: #fc7103;
  }
</style>