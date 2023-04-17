<template>
  <div id="app">
	 <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
  /* CSS reset */
  html{color:#000;background:#fff;-webkit-tap-highlight-color:rgba(0,0,0,0);font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";font-size: 12px;}
  body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,form,input,button,textarea,p,th,td,strong{padding:0;margin:0;font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";}
  table{border-collapse:collapse;border-spacing:0;}
  img{border:0;}
  a{text-decoration:none; color:#999; outline:none;}/*此处待添加默认链接颜色*/
  var,em,strong{font-style:normal;}
  em,strong,th,var{font-style:inherit;font-weight:inherit;}
  li{list-style:none;}
  caption,th{text-align:left;}
  h1,h2,h3,h4{font-size:100%;font-weight:normal;}
  input,button,textarea,select,option{font-family:inherit; font-size:inherit;font-style:inherit;font-weight:inherit;}
  input,button,textarea,select{*font-size:100%;}
  .clearfix:after {content:"\200B"; display:block; height:0; clear:both; }
  .clearfix { *zoom:1; }


  html {
    position: relative;
    width: 100%;
    overflow: hidden;
    overflow-y: scroll;
  }
  #app {
  }
  .pc {
    width: 100%;
    overflow: hidden;
  }
  .selection {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }

  .mob {
    display: none;
  }

  .top {
    display: none;
    position: fixed;
    right: 3.96vw;
    bottom: 50vh;
    z-index: 99999;
    cursor: pointer;
  }
  .top img {
    width: 4.17vw;
    height: 4.17vw;
  }
  
  .down {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 4.58vw;
    text-align: center;
    font-family: PingFangSC-Medium;
    font-size: 1.46vw;
    color: #FFFFFF;
    cursor: pointer; 
  }
  
  .down img {
    display: block;
    width: 3.18vw;
    margin: 0 auto;
    -webkit-animation: fall 1.2s infinite;
    animation: fall 1.2s infinite;
  }

  .tit .p {
    position: relative;
    width: -webkit-max-content;
    width: -moz-max-content;
    width: max-content;   
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #000000;
    z-index: 2;
  }
  .tit .p::after {
    content: '';
    position: absolute;
    left: -2vw;
    top: -1vh;
    width: 7.97vw;
    height: 2.19vw;
    background: url('./assets/span.png') center center no-repeat;
    background-size: 100% 100%;
    z-index: -1;
  }


  .selection-4 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
    width: 0.42vw;
    height: 0.42vw;
    border: 1px solid #E0E0E0;
    margin: 0 0.26vw;
    display: inline-block;
    border-radius: 100%;
    background: #fff;
    opacity: 1;
  }
  .selection-4 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
    opacity: 1;
    border: 1px solid #979797;
  }


  /*向下效果*/
  @-webkit-keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  @keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }

  @media screen and (max-width: 750px) {
    .mob {
      display: block;
    }
    .pc {
      display: none;
    }

    .top {
      display: none;
      position: fixed;
      right: 7.47vw;
      bottom: 50vh;
      z-index: 99999;
      cursor: pointer;
    }
    .top img {
      width: 8vw;
      height: 8vw;
    }

    .down {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 4.58vw;
      text-align: center;
      font-family: PingFangSC-Medium;
      font-size: 1.46vw;
      color: #FFFFFF;
      cursor: pointer; 
    }
    
    .down img {
      display: block;
      width: 8vw;
      margin: 0 auto;
      -webkit-animation: fall 1.2s infinite;
      animation: fall 1.2s infinite;
    }

    .tit .p {
      position: relative;
      width: -webkit-max-content;
      width: -moz-max-content;
      width: max-content;   
      font-family: PingFangSC-Medium;
      font-size: 4.8vw;
      color: #000000;
      z-index: 2;
    }
    .tit .p::after {
      content: '';
      position: absolute;
      left: -2vw;
      top: -1vh;
      width: 16.53vw;
      height: 5.33vw;
      background: url('./assets/span.png') center center no-repeat;
      background-size: 100% 100%;
      z-index: -1;
    }

  }

</style>
