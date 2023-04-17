<template>
  	<header>
	  	<div class="pc">
        <div class="cont">
          <a class="logo" @click="jump" ><img src="../assets/PClogo@3x.svg" alt=""></a>
          <p class="title">一个完全自主的拍卖平台</p>
          <ul class="nav">
            <li class="backstage"><a href="#">后台登陆</a></li>
          </ul>
        </div>
	  	</div>
	  	<div class="mob">
        <div class="cont">
          <a class="logo" @click="jump" ><img src="../assets/PClogo@3x.svg" alt=""></a>
        </div>
	  	</div>
    </header>
</template>

<script>
let storage = window.sessionStorage;
export default {
  name: 'Header',
  data () {
    return {
    	navData: [
    		{tit: '首页', links:'/'},
        ],
      	num: '',
      	selShow: false
    }
  },
  created: function() {
    if(storage['selNumxinhongtu']) {
      this.num = storage['selNumxinhongtu'];
    } else {
      this.num = 0;
    };
  },
  methods: {
    selMenus(index) {
      storage['selNumxinhongtu'] = index;
      this.selShow = false;
    },
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.selShow = ! this.selShow;
    },
    jump() {
      storage['selNumxinhongtu'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .cont {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 6.77vw;
    background: #FFFFFF;
    z-index: 9999;
  }
  .logo {
    flex: 1;
    display: flex;
    justify-content: center;
  }
  .logo img {
    width: 10.68vw;
  }
  .title {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    font-family: PingFangSC-Light;
    font-size: 1.56vw;
    color: #9F9F9F;
  }

  .title::after {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    bottom: -0.5vw;
    width: 10.42vw;
    height: 1px;
    margin: 0 auto;
    opacity: 0.56;
    background: #D8D8D8;
  }
  .nav {
    flex: 1;
    display: flex;
    justify-content: center;
  }
  .backstage {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 10.4vw;
    height: 3.8vw;
    background: #FFFFFF;
    border: 1px solid #E15100;
    box-shadow: 3px 4px 9px 0 rgba(225,81,0,0.16);
    border-radius: 100px;
  }
  .backstage a {
    font-family: PingFangSC-Regular;
    font-size: 1.77vw;
    color: #E15100;
  }
  
	
	@media screen and (max-width: 750px) {
		.pc {
			display: none;
		}

    .cont {
      height: 21.33vw;
      padding-left: 12vw;
    }
    .logo {
      flex: 1;
      display: flex;
      justify-content: flex-start;
    }
    .logo img {
      width: 20.33vw;
    }
		
	}

	@media screen and (min-width: 751px) {
		
	}
</style>
