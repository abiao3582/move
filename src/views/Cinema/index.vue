<template>
  <div>
    <Header title="喵喵影院"/>
    <div>
      <div class="cinema_menu">
        <div class="city_switch">
          全城<i class="iconfont icon-lower-triangle"></i>
        </div>
        <div class="brand_switch">
          品牌<i class="iconfont icon-lower-triangle"></i>
        </div>
        <div class="feature_switch">
          特色<i class="iconfont icon-lower-triangle"></i>
        </div>
      </div>
      <keep-alive>
        <router-view/>
      </keep-alive>
    </div>
    <TabBar/>
    
  </div>
</template>

<script>

import Header from '@/components/Header';
import TabBar from '@/components/TabBar';

export default {
  name:'cinema',
  components:{
    Header,
    TabBar,
  }
}
</script>

<style>
  
  .cinema_menu{
  width: 100%;
  height: 45px;
  margin-top: 51px;
  /* 触发弹性盒，父元素设置子元素触发 */
  display: flex;
  border-bottom: 1px solid #e6e6e6;
  /* 主轴的对齐方式 */
  justify-content: space-between;
  font-size: 18px;
  line-height: 45px;
  text-align: center;
}
.cinema_menu .city_switch{
  margin-left: 20px;
}
.cinema_menu .feature_switch{
  margin-right: 20px;
}
</style>