<template>
  <footer>
  	<div class="pc">
      <div class="left">
        <div class="con">
          <h2>打造自己的自主拍卖专属平台！</h2>
          <p>TEL：400-861-8089<br/>
            QQ：2608959680<br/>
            ADD：厦门市思明区观音山商务营运中心18号4层 
          </p> 
          </div>
      </div>
      <div class="right">
        <div class="list_div">
          <img src="../assets/pcewm@2x.png" alt="">
          <p>扫一扫体验小程序</p>
        </div>
        <div class="list_div">
          <img src="../assets/pcewm@2x.png" alt="">
          <p>扫一扫识别二维码</p>
        </div>
      </div>
  	</div>
  	<div class="mob">
      <div class="cons">
        <h2>打造自己的自主拍卖专属平台！</h2>
        <p>TEL：400-861-8089</p>
        <p>ADD：厦门市思明区观音山商务营运中心18号4层</p>
      </div>
  	</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  footer {
    height: 21.85vh;
    background: #323232;
  }
  .pc {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .left {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 25.98vw;
  }
  h2 {
    margin-bottom: 1.3vh;
    font-family: PingFangSC-Light;
    font-size: 1.56vw;
    color: #FFFFFF;
  }
  p {
    font-family: PingFangSC-Regular;
    font-size: 1.04vw;
    color: #A7A7A7;
    line-height: 2.14vw;
  }
  .right {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .list_div {
    margin: 0 2.55vw;
  }
  .list_div img {
    display: block;
    width: 6.46vw;
    height: 6.46vw;
    margin: 0 auto 1.48vh;
  }
  .list_div p {
    font-family: PingFangSC-Light;
    font-size: 1.04vw;
    color: #FFFFFF;
  }
  

  

	@media screen and (max-width: 750px) {
    .pc {
      display: none;
    }
		.mob {
	    display: block;
      height: 100%;
	  }
    footer {
      height: 17.99vh;
      background: #323232;
    }
    .cons {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
    }
    h2 {
      margin-bottom: 1.3vh;
      font-family: PingFangSC-Light;
      font-size: 3.73vw;
      color: #FFFFFF;
    }
    p {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #A7A7A7;
      text-align: center;
      line-height: 5.87vw;
    }

	}

</style>
