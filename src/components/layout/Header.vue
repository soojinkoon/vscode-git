
<!-- [개별 템플릿 (뷰) 설정 실시] -->
<template>
    <div>
      <h1>{{ msg }}</h1>
    </div>
  </template>
  
  
  
  
  
  <!-- [개별 스크립트 설정 실시] -->
  <script>
  export default {
    name: 'MainComponent',
    props: {
      msg: String
    }
  }
  
  /* [html 최초 로드 및 이벤트 상시 대기 실시] */
  window.onload = function() {
      console.log("");
      console.log("[MainComponent] : [window onload] : [start]");
      console.log("");
  };
  
  </script>
  
  
  
  
  
  <!-- [개별 스타일 설정 실시] -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  </style>
   
  