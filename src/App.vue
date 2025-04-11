<template>
  <!-- 需要一个动态区域根据 URL 变化显示不同内容。类比理解：<router-view> 相当于传统网站中 <body> 的主体内容区域，但具备动态更新能力 -->
  <router-view></router-view>
</template>

<style>
body {
  height: 100%;
  width: 100%;
  position: absolute;
  margin: 0;
  padding: 0;
  background-color: #f1f1f1;
}
.content-container {
  background-color: white;
  padding: 20px;
  margin: 20px;
  border-radius: 10px;
  min-width:1200px;
  display:inline-block; 
  width:90%;
}
.input-tip {
  margin: 0 10px;
  line-height: 40px;
}
.input-field {
  margin-right: 40px;
}
.content-row {
  margin-bottom: 20px;
}
</style>