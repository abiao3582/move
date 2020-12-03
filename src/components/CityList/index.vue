<template>
  <div class="cinema_body">
    <ul>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>大地影院(敖东实际店)</span>
          <span class="p"><span class="price">22.9</span>元起</span>
        </div>
        <div class="address">
          <span>金州区大连经济开发区敖东实际3层</span>
          <span>138m</span>
        </div>
        <div class="card">
          <div>小吃</div>
          <div>折扣卡</div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name:'CityList'
}
</script>

<style>
  .cinema_body{
    flex: 1;
    overflow: auto;
  }
  .cinema_body ul{
    margin: 12px;
  }
  .cinema_body li{
    height: 100px;
    width: 100%;
    border-bottom: 1px solid #ccc;
    
  }
   li div:nth-child(1) span:nth-child(1){
     font-size: 20px;
     font-weight: 600px;
     line-height: 40px;
   }
  .cinema_body .p {
    color: red;
  }
  .cinema_body .p .price{
    font-size: 25px;
  }
  li .address span:nth-child(2){
    float: right;
  }
  .cinema_body li .card{
    display: flex;
  }
  .cinema_body li .card div{
    border: 1px solid rgb(206, 206, 33);
    color: yellow;
    font-size: 12px;
    padding: 2px;
    margin: 3px;
  }

</style>