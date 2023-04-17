<template>
  <div class="home">
    <div class="pc">
      <app-header></app-header>
      <div class="top"><img src="../assets/pcfhdb copy@3x.svg" alt=""></div>
      <div class="selection selection-1">
        <div class="cont">
          <!-- <h2>Edge</h2> -->
          <h3>基于区块链底层技术的<span>“去中心化”</span>微拍卖小程序<br/>
          一个完全自主的拍卖平台</h3>
          <div class="code-con">
            <img src="../assets/pcewm@2x.png" alt="">
            <p>扫码立即体验</p>
          </div>
          <div class="down" @click="slideDown">
            <img src="../assets/pcwangxia@3x.svg" alt="">
          </div>
        </div>
      </div>
      <div class="selection selection-2">
        <div class="cont">
          <div class="tit">
            <div class="p">采用第三方平台从商的几大危机</div>
          </div>
          <div class="list">
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/a@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_01"></div>
                <!-- <img src="../assets/pcyingiao@3x.svg" alt=""> -->
                <p>客户被掠夺</p>
              </div>
            </div>
            <div class="list_div">
              <div class="list-bottom">
                <div class="img img_02"></div>
                <!-- <img src="../assets/pcqudo@3x.svg" alt=""> -->
                <p>无奈的霸王条约</p>
              </div>
              <div class="list-top list-top-c">
                <img src="../assets/b@2x.png" alt="">
                <div class="span-b"></div>
              </div>
            </div>
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/aa@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_03"></div>
                <!-- <img src="../assets/pcjiesuanz@3x.svg" alt=""> -->
                <p>运营成本高</p>
              </div>
            </div>
            <div class="list_div">
              <div class="list-bottom">
                <div class="img img_04"></div>
                <!-- <img src="../assets/pcyionghutiy@3x.svg" alt=""> -->
                <p>资金被占用</p>
              </div>
              <div class="list-top list-top-c">
                <img src="../assets/cc@2x.png" alt="">
                <div class="span-b"></div>
              </div>
            </div>
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/d@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_05"></div>
                <!-- <img src="../assets/pcguangg@3x.svg" alt=""> -->
                <p>经营模式受局限</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-3">
        <div class="cont">
          <div class="tit">
            <div class="p">“Edge”平台7大基础功能</div>
          </div>
          <div class="list">
            <div class="list_div">
              <img src="../assets/pclldr.svg" alt="">
              <p>专属小程序</p>
            </div>
            <div class="list_div">
              <img src="../assets/pczaf.svg" alt="">
              <p>流量导入</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcspfw.svg" alt="">
              <p>商品&服务管理</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcfensiqd.svg" alt="">
              <p>粉丝&渠道管理</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcguangtt.svg" alt="">
              <p>统计分析</p>
            </div>
            <div class="list_div">
              <img src="../assets/pctjfx.svg" alt="">
              <p>营销推广工具</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcyxtggj.svg" alt="">
              <p>广告投放</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-4">
        <div class="cont">
          <div class="tit">
            <div class="p">Edge平台几大优势</div>
          </div>
          <div class="list-con">
            <div class="left">
              <img src="../assets/pcbj4@2x.jpg" alt="">
            </div>
            <div class="right">
              <div class="label">PECULIARITY</div>
              <div class="swiper-con">
                <p><span>1</span>拥有成本低、无需开发</p>
                <p><span>2</span>自主经营、随心所欲</p>
                <p><span>3</span>客户付款秒到、无账期</p>
                <p><span>4</span>保护客户不被掠夺</p>
                <p><span>5</span>突破瓶颈客户数量上限</p>
                <p style="margin-bottom: 0"><span>6</span>安装、维护、升级无忧</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-5">
        <div id="swiper05" class="swiper-container clearfix">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="cont">
                <div class="tit">
                  <div class="p">平台展示</div>
                </div>
                <div class="list">
                  <div class="list_div">
                    <p>首页（UI图）</p>
                    <img src="../assets/4@2x.jpg" alt="">
                  </div>
                  <div class="list_div">
                    <p>商家报表（UI图）</p>
                    <img src="../assets/5@2x.jpg" alt="">
                  </div>
                  <div class="list_div">
                    <p>单品页（UI图）</p>
                    <img src="../assets/1@2x.jpg" alt="">
                  </div>
                  <div class="list_div">
                    <p>拍卖（UI图）</p>
                    <img src="../assets/2@2x.jpg" alt="">
                  </div>
                  <div class="list_div">
                    <p>一口价（UI图）</p>
                    <img src="../assets/3@2x.jpg" alt="">
                  </div>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont">
                <div class="tit">
                  <div class="p">优势分析</div>
                </div>
                <img class="yous-img" src="../assets/pcdabg@2x.png" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="selection selection-6">
        <div class="cont">
          <div class="tit">
            <div class="p">优秀案例</div>
          </div>
          <div class="list">
            <div class="list_div">
              <img src="../assets/pcbj13@2x.jpg" alt="">
              <h3>海艺东方</h3>
              <p>欧洲老货瓷杂回流</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj12@2x.jpg" alt="">
              <h3>大兴堂</h3>
              <p>紫砂茶道专业品牌</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj11@2x.jpg" alt="">
              <h3>雅玩文化</h3>
              <p>古典雅玩珍藏文化推行者</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj10@2x.jpg" alt="">
              <h3>玉翠情怀（钻石城）</h3>
              <p>翡翠珠宝源头供货商</p>
            </div>
          </div>
        </div>
      </div> -->
      <div class="selection selection-7">
        <div class="cont">
          <div class="tit">
            <div class="p">如何快速入驻？</div>
          </div>
          <div class="list">
            <div class="list_div">
              <div class="img-con">
                <img class="ewm" src="../assets/pcewm@2x.png" alt="">
              </div>
              <p>扫码小程序二维码<br/>立即开通</p>
            </div>
            <img class="next" src="../assets/pcjiantou@3x.svg" alt="">
            <div class="list_div">
              <img src="../assets/4@2x.jpg" alt="">
              <p>进入首页<br/>（点击中间红色按钮）</p>
            </div>
            <img class="next" src="../assets/pcjiantou@3x.svg" alt="">
            <div class="list_div">
              <img src="../assets/8@2x.jpg" alt="">
              <p>立即申请</p>
            </div>
            <img class="next" src="../assets/pcjiantou@3x.svg" alt="">
            <div class="list_div">
              <img src="../assets/7@2x.jpg" alt="">
              <p>填写资料完成申请</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-8">
        <div class="cont">
          <div class="tit">
            <div class="p">开通流程及服务范围</div>
          </div>
          <div class="list">
            <div class="list_div">
              <span>1.</span><p>提交资料，等待开通</p>
            </div>
            <div class="list_div">
              <span>2.</span><p>工作人员48小时内与您联系</p>
            </div>
            <div class="list_div">
              <span>3.</span><p>7个工作日内开通平台，交付使用</p>
            </div>
            <div class="list_div">
              <span>4.</span><p>免费提供运营指导，协助您快速系统上线</p>
            </div>
            <div class="list_div">
              <span>5.</span><p>提供专业的售后服务</p>
            </div>
          </div>
        </div>
        <app-footer></app-footer>
      </div>
    </div>
    <div class="mob">
      <app-header></app-header>
      <div class="top"><img src="../assets/pcfhdb copy@3x.svg" alt=""></div>
      <div class="selection selection-1">
        <div class="cont">
          <h2>Edge</h2>
          <div class="h3">
            <h3>基于区块链底层技术的 “ 去中心化 ” 微拍卖小程序</h3>
            <h3>一个完全自主的拍卖平台</h3>
          </div>
          <div class="code-con">
            <img src="../assets/pcewm@2x.png" alt="">
            <p>长按识别二维码<br/>
            立即体验</p>
          </div>
          <div class="down" @click="slideDown">
            <img src="../assets/pcwangxia@3x.svg" alt="">
          </div>
        </div>
      </div>
      <div class="selection selection-2">
        <div class="cont">
          <div class="tit">
            <div class="p">采用第三方平台从商的几大危机</div>
          </div>
          <div class="list">
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/a@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_01"></div>
                <p>客户被掠夺</p>
              </div>
            </div>
            <div class="list_div">
              <div class="list-bottom">
                <div class="img img_02"></div>
                <p>无奈的霸王条约</p>
              </div>
              <div class="list-top list-top-c">
                <img src="../assets/b@2x.png" alt="">
                <div class="span-b"></div>
              </div>
            </div>
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/aa@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_03"></div>
                <p>运营成本高</p>
              </div>
            </div>
            <div class="list_div">
              <div class="list-bottom">
                <div class="img img_04"></div>
                <p>资金被占用</p>
              </div>
              <div class="list-top list-top-c">
                <img src="../assets/cc@2x.png" alt="">
                <div class="span-b"></div>
              </div>
            </div>
            <div class="list_div">
              <div class="list-top">
                <img src="../assets/d@2x.png" alt="">
                <div class="span-b"></div>
              </div>
              <div class="list-bottom">
                <div class="img img_05"></div>
                <p>经营模式受局限</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-3">
        <div class="cont">
          <div class="tit">
            <div class="p">“Edge”平台7大基础功能</div>
          </div>
          <div class="list">
            <div class="list_div">
              <img src="../assets/pclldr.svg" alt="">
              <p>专属小程序</p>
            </div>
            <div class="list_div">
              <img src="../assets/pczaf.svg" alt="">
              <p>流量导入</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcspfw.svg" alt="">
              <p>专属商品&服务管理程序&账户</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcfensiqd.svg" alt="">
              <p>粉丝&渠道管理</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcguangtt.svg" alt="">
              <p>统计分析</p>
            </div>
            <div class="list_div">
              <img src="../assets/pctjfx.svg" alt="">
              <p>营销推广工具</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcyxtggj.svg" alt="">
              <p>广告投放</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-4">
        <div class="cont">
          <div class="tit">
            <div class="p">Edge平台几大优势</div>
          </div>
          <div class="list-con">
            <div class="right">
              <div class="label">PECULIARITY</div>
              <div class="swiper-con">
                <p><span>1</span>拥有成本低、无需开发</p>
                <p><span>2</span>自主经营、随心所欲</p>
                <p><span>3</span>客户付款秒到、无账期</p>
                <p><span>4</span>保护客户不被掠夺</p>
                <p><span>5</span>突破瓶颈客户数量上限</p>
                <p><span>6</span>安装、维护、升级无忧</p>
              </div>
            </div>
            <div class="left">
              <img src="../assets/pcbj4@2x.jpg" alt="">
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-5">
        <div class="cont">
          <div class="tit">
            <div class="p">平台展示</div>
          </div>
          <div id="swiper005" class="swiper-container clearfix">
            <div class="swiper-wrapper">
              <div class="swiper-slide">
                <div class="list_div">
                  <p>首页（UI图）</p>
                  <img src="../assets/4@2x.jpg" alt="">
                </div>
              </div>
              <div class="swiper-slide">
                <div class="list_div">
                  <p>商家报表（UI图）</p>
                  <img src="../assets/5@2x.jpg" alt="">
                </div>
              </div>
              <div class="swiper-slide">
                <div class="list_div">
                  <p>单品页（UI图）</p>
                  <img src="../assets/1@2x.jpg" alt="">
                </div>
              </div>
              <div class="swiper-slide">
                <div class="list_div">
                  <p>拍卖（UI图）</p>
                  <img src="../assets/2@2x.jpg" alt="">
                </div>
              </div>
              <div class="swiper-slide">
                <div class="list_div">
                  <p>一口价（UI图）</p>
                  <img src="../assets/3@2x.jpg" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-5">
        <div class="cont">
          <div class="tit">
            <div class="p">优势分析</div>
          </div>
          <img class="yous-img" src="../assets/yddbg@2x.png" alt="">
        </div>        
      </div>
      <!-- <div class="selection selection-6">
        <div class="cont">
          <div class="tit">
            <div class="p">优秀案例</div>
          </div>
          <div class="list">
            <div class="list_div">
              <img src="../assets/pcbj13@2x.jpg" alt="">
              <h3>海艺东方</h3>
              <p>欧洲老货瓷杂回流</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj12@2x.jpg" alt="">
              <h3>大兴堂</h3>
              <p>紫砂茶道专业品牌</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj11@2x.jpg" alt="">
              <h3>雅玩文化</h3>
              <p>古典雅玩珍藏文化推行者</p>
            </div>
            <div class="list_div">
              <img src="../assets/pcbj10@2x.jpg" alt="">
              <h3>玉翠情怀（钻石城）</h3>
              <p>翡翠珠宝源头供货商</p>
            </div>
          </div>
        </div>
      </div> -->
      <div class="selection selection-7">
        <div class="cont">
          <div class="tit">
            <div class="p">如何快速入驻？</div>
          </div>
          <div class="list" style="margin-bottom: 8.85vh">
            <div class="list_div">
              <div class="img-con">
                <img class="ewm" src="../assets/pcewm@2x.png" alt="">
              </div>
              <p>扫码小程序二维码<br/>立即开通</p>
            </div>
            <div class="next">
              <span>1</span>
              <img src="../assets/pcjiantou@3x.svg" alt="">
            </div>
            <div class="list_div">
              <img src="../assets/4@2x.jpg" alt="">
              <p>进入首页<br/>（点击中间红色按钮）</p>
            </div>
            <div class="next next-c">
              <span>2</span>
              <img src="../assets/pcjiantou@3x.svg" alt="">
            </div>
          </div>
          <div class="list">
            <div class="list_div">
              <img src="../assets/8@2x.jpg" alt="">
              <p>立即申请</p>
            </div>
            <div class="next">
              <span>3</span>
              <img class="s-next" src="../assets/pcjiantou@3x.svg" alt="">
            </div>
            <div class="list_div">
              <img src="../assets/7@2x.jpg" alt="">
              <p>填写资料完成申请</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-8">
        <div class="cont">
          <div class="tit">
            <div class="p">开通流程及服务范围</div>
          </div>
          <div class="list">
            <div class="list_div">
              <span>1.</span><p>提交资料，等待开通</p>
            </div>
            <div class="list_div">
              <span>2.</span><p>工作人员48小时内与您联系</p>
            </div>
            <div class="list_div">
              <span>3.</span><p>7个工作日内开通平台，交付使用</p>
            </div>
            <div class="list_div">
              <span>4.</span><p>免费提供运营指导，协助您快速系统上线</p>
            </div>
            <div class="list_div">
              <span>5.</span><p>提供专业的售后服务</p>
            </div>
          </div>
        </div>
        <app-footer></app-footer>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './Header'
import Footer from './Footer'

export default {
  name: 'Home',
  data () {
    return {
      selShow: false,
    }
  },
  created() {

  },
  methods: {
    slideDown() {
      let downHeight = document.documentElement.clientHeight || document.body.clientHeight;
      window.scrollTo(0, downHeight);
      this.slideShow = true;
    },
  },
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  mounted() {
    // 返回顶部
    $('.top').on('click', function() {
      console.log(233);
      $('html, body').animate({scrollTop: '0px'}, 800);
    });

    $(window).scroll(function() {
    　　 var scrollTop = $(this).scrollTop();
    　　 var scrollHeight = $(document).height();
    　　 var windowHeight = $(this).height();

      if(scrollTop < scrollHeight / 8) {
        $('.top').css({
          'display': 'none'
        });
      } else {
        $('.top').css({
          'display': 'block'
        });
      }
    });


    let swiper04 = new Swiper('#swiper04, #swiper04_', {
      loop: 1,
      autoplay: 3000,
      autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 0,
      speed: 300,
      releaseOnEdges: true,
      paginationClickable: true,
      noSwiping : true,
      pagination: '.swiper-pagination',
      prevButton: '.selection-4 .pre-btn',
      nextButton: '.selection-4 .next-btn',
    });

    let swiper05 = new Swiper('#swiper05', {
      loop: false,
      direction: 'vertical',
      // autoplay: 3000,
      autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 0,
      speed: 300,
      releaseOnEdges: true,
      mousewheelControl: true,
      paginationClickable: true,
      noSwiping : true,
    });

    let swiper005 = new Swiper('#swiper005', {
      loop: true,
      // direction: 'vertical',
      autoplay: 3000,
      centeredSlides: true,
      autoplayDisableOnInteraction : false,
      slidesPerView: 2,
      spaceBetween: 0,
      speed: 300,
      releaseOnEdges: true,
      mousewheelControl: true,
      paginationClickable: true,
      noSwiping : true,
    });

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  /*selection-1*/
  .selection-1 {
    background: url('../assets/pcbj.jpg') center center no-repeat;
    background-size: cover;
  }

  .selection-1 .cont {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-direction: column;
    width: 80%;
    height: 100%;
    margin: 0 auto;
  }

  .selection-1 h2 {
    margin-bottom: 1.76vh;
    font-family: PingFangSC-Regular;
    font-size: 4.69vw;
    color: #E15100;
    letter-spacing: -2.17px;
  }
  .selection-1 h3 {
    font-family: PingFangSC-Thin;
    font-size: 2.81vw;
    color: #DCDCDC;
    letter-spacing: -1.21px;
  } 
  .selection-1 h3 span {
    color: #E15100;
  }

  .selection-1 .code-con {
    position: absolute;
    right: 12.4vw;
    bottom: 12.22vh;
  }
  .selection-1 .code-con img {
    display: block;
    width: 9.38vw;
    height: 9.38vw;
    margin: 0 auto 1.2vh;
  }
  .selection-1 .code-con p {
    text-align: center;
    font-family: PingFangSC-Regular;
    font-size: 1.35vw;
    color: #C2C2C2;
    letter-spacing: -0.63px;
  }
  

  /*selection-2*/
  .selection-2 {
    background: url('../assets/pcbej.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-2 .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100%;
  }

  .selection-2 .tit {
    margin-bottom: 13.89vh;
  }
  
  .selection-2 .list {
    display: flex;
  }

  .selection-2 .list_div {
    width: 14vw;
    cursor: pointer;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }
  .selection-2 .list-top {
    position: relative;
    height: 14.37vw;
  }
  .selection-2 .list-top img {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
    width: 7.19vw;
    height: auto;
    z-index: 2;
  }
  .selection-2 .list-top .span-b {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 11.67vh;
    background: #1E1E1E;
    z-index: 1;
  }
  .selection-2 .list-top-c .span-b {
    position: absolute;
    left: 0;
    top: 0;
  }
  .selection-2 .list-bottom {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 14.37vw;
    background: #FFF;
  }

  .selection-2 .list-bottom .img {
    width: 4.17vw;
    height: 4.17vw;
    margin: 0 auto 3.89vh;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }
  

  .selection-2 .list-bottom .img_01 {
    background: url('../assets/pcyingiao@3x.svg') center center no-repeat;
    background-size: 100% 100%;
  }
  .selection-2 .list-bottom .img_02 {
    background: url('../assets/pcqudo@3x.svg') center center no-repeat;
    background-size: 100% 100%;
  }
  .selection-2 .list-bottom .img_03 {
    background: url('../assets/pcjiesuanz@3x.svg') center center no-repeat;
    background-size: 100% 100%;
  }
  .selection-2 .list-bottom .img_04 {
    background: url('../assets/pcyionghutiy@3x.svg') center center no-repeat;
    background-size: 100% 100%;
  }
  .selection-2 .list-bottom .img_05 {
    background: url('../assets/pcguangg@3x.svg') center center no-repeat;
    background-size: 100% 100%;
  }

  .selection-2 .list_div p {
    font-family: PingFangSC-Regular;
    font-size: 1.15vw;
    color: #505050;
    letter-spacing: -0.53px;   
  }


  /*selection-3*/
  .selection-3 {
    background: url('../assets/pcbj1@1x.jpg') center center no-repeat;
    background-size: cover;
  }
  
  .selection-3 .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100%;
  }

  .selection-3 .tit {
    margin-bottom: 13.7vh;
  }

  .selection-3 .tit .p {
    color: #fff;
  }

  .selection-3 .list {
    display: flex;
    align-items: center;
  }
  
  .selection-3 .list .list_div img {
    width: 3.65vw;
    height: 3.65vw;
    margin-bottom: 5.83vh;
  }

  .selection-3 .list .list_div p {
    position: relative;
    width: 1.88vw;
    height: 13.54vw;
    margin-right: 2.45vw;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #FFFFFF; 
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }

  .selection-3 .list .list_div p::after {
    content: '';
    position: absolute;
    right: -2.45vw;
    top: 0;
    width: 1px;
    height: 100%;
    opacity: 0.71;
    background: #D8D8D8;
  }
  
  .selection-3 .list .list_div:hover {
    background: rgba(255, 255, 255, 1);
  }
  .selection-3 .list .list_div:hover p {
    color: #000; 
  }

  .selection-3 .list .list_div:hover p::after {
    background: #000;
  }



  /*selection-4*/
  .selection-4 {
    background: url('../assets/pcbj2.jpg') center center no-repeat;
    background-size: cover;
  }
  
  .selection-4 .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100%;
  }

  .selection-4 .tit {
    margin-bottom: 16.76vh;
  }

  .selection-4 .tit .p {
    color: #fff;
  }

  .selection-4 .list-con {
    display: flex;
    justify-content: center;
  }

  .selection-4 .left {
    margin-top: 2.96vh;
  }
  .selection-4 .left img {
    width: 18.8vw;
  }
  .selection-4 .right {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    position: relative;
    width: 27.08vw;
    height: 29.22vw;
    background: #FFFFFF;
  }
  .selection-4 .right .label {
    position: absolute;
    top: 2.9vw;
    right: -2.92vw;
    transform: rotate(-270deg);
    font-family: PingFangSC-Medium;
    font-size: 2.6vw;
    color: #C8C8C8;
    letter-spacing: -1.21px;    
  }

  .selection-4 .right p {
    margin-bottom: 4.17vh;
    padding-left: 2.66vw;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    letter-spacing: -0.58px;
  }
  .selection-4 .right p span {
    display: inline-block;
    width: 1.41vw;
    height: 1.41vw;
    margin-right: 1.3vw;
    border-radius: 50%;
    text-align: center;
    background: #E15100;
    font-family: PingFangSC-Regular;
    font-size: 1.04vw;
    color: #FFFFFF;
    line-height: 1.41vw;
  }



  /*selection-5*/
  .selection-5 {
    background: url('../assets/pcdbj7.jpg') center center no-repeat;
    background-size: cover;
  }
  
  .selection-5 .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100%;
  }

  .selection-5 .tit {
    margin-bottom: 8.7vh;
  }

  .selection-5 .tit .p {
    color: #fff;
  }
  
  #swiper05 {
    width: 85vw;
    height: 100vh;
    margin: 0 auto;
  }
 
  .selection-5 .list {
    display: flex;
    justify-content: center;
  }

  .selection-5 .list_div {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    flex-direction: column;
    margin: 0 2.08vw;
  }
  .selection-5 .list_div p {
    margin-bottom: 1.85vh;
    font-family: PingFangSC-Regular;
    font-size: 1.15vw;
    color: #FFFFFF;
    letter-spacing: -0.53px;
  }
  .selection-5 .list_div img {
    width: 11.56vw;
  }

  .selection-5 .yous-img {
    width: 60.73vw;
  }
  
  /*selection-6*/
  .selection-6 {
    background: url('../assets/pcbj8.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-6 .cont {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 100vw;
    height: 100%;
  }
  .selection-6 .tit {
    margin-bottom: 21.02vh;
  }
  .selection-6 .list {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .selection-6 .list_div {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-right: 0.47vw;
  }
  .selection-6 .list_div img {
    width: 24.64vw;
    height: 16.61vw;
    margin-bottom: 2.87vh;
  }
  .selection-6 .list_div h3 {
    display: block;
    width: 100%;
    text-align: left;
    margin-left: 2.55vw;
    margin-bottom: 1.11vh;
    font-family: PingFangSC-Medium;
    font-size: 1.67vw;
    color: #000000;
    letter-spacing: -0.77px;
  }
  .selection-6 .list_div p {
    display: block;
    width: 100%;
    text-align: left;
    margin-left: 2.55vw;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #505050;
    letter-spacing: -0.58px;
  }

  /*selection-7*/
  .selection-7 {
    background: #F9F9F9;
  }
  .selection-7 .cont {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 100vw;
    height: 100%;
  }
  .selection-7 .tit {
    margin-bottom: 13.8vh;
  }
  .selection-7 .list {
    display: flex;
    align-items: center;
  }
  .selection-7 .list .next {
    width: 3.54vw;
    height: 2.86vw;
    margin: 0 1.98vw 11vh 1.98vw;
  }
  .selection-7 .list_div {
    height: 31.04vw;
  }
  .selection-7 .list_div img {
    width: 14.32vw;
    height: 25.52vw;
    margin-bottom: 3.7vh;
  }
  .selection-7 .list_div .img-con {
    display: flex;
    align-items: center;
    height: 25.52vw;
    margin-bottom: 3.7vh;
  }
  .selection-7 .list_div .ewm {
    width: 13.02vw;
    height: 13.02vw;
  }
  .selection-7 .list_div p {
    height: 3.44vw;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    text-align: center;
  }
  
  /*selection-8*/
  .selection-8 {

  }
  .selection-8 .cont {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-direction: column;
    height: 78.15vh;
    padding-left: 17.5vw;
    background: url('../assets/pcbjdb.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-8 .tit {
    margin-bottom: 10.28vh;
  }

  .selection-8 .list {

  }
  .selection-8 .list_div {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 28.91vw;
    height: 3.33vw;
    margin-bottom: 2.22vh;
    background: rgba(255, 255, 255, 0.56);
    cursor: pointer;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }
  .selection-8 .list_div span {
    display: inline-block;
    margin-right: 2.81vw;
    margin-left: 3.02vw;
    font-family: PingFangSC-Medium;
    font-size: 1.56vw;
    color: #001436;
    letter-spacing: -0.72px;
  }
  .selection-8 .list_div p {
    font-family: PingFangSC-Regular;
    font-size: 1.15vw;
    color: #001436;
    letter-spacing: -0.53px;
  }
  
  .selection-8 .list_div:hover {
    background: #000;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }
  .selection-8 .list_div:hover p {
    color: #fff;
  }
  .selection-8 .list_div:hover span {
    color: #fff;
  }
  

  @media screen and (max-width: 750px) {
    /*selection-1*/
    .selection-1 {
      background: url('../assets/yddbj1@2x.jpg') center center no-repeat;
      background-size: cover;
    }

    .selection-1 .cont {
      display: flex;
      justify-content: center;
      align-items: flex-start;
      flex-direction: column;
      width: 80%;
      height: 100%;
      margin: 0 auto;
    }

    .selection-1 h2 {
      margin-bottom: 3vh;
      font-family: PingFangSC-Regular;
      font-size: 10.67vw;
      color: #E15100;
      letter-spacing: -0.96px;
    }
    .selection-1 .h3 {
      display: flex;
    }
    .selection-1 h3 {
      width: 4vw;
      height: 100%;
      margin-right: 6.13vw;
      font-family: PingFangSC-Thin;
      font-size: 2.6vw;
      color: #DCDCDC;
      letter-spacing: -1.21px;
    } 

    .selection-1 .code-con {
      position: absolute;
      right: 12.4vw;
      bottom: 12.22vh;
    }
    .selection-1 .code-con img {
      display: block;
      width: 21.87vw;
      height: 21.87vw;
      margin: 0 auto 1.05vh;
    }
    .selection-1 .code-con p {
      text-align: center;
      font-family: PingFangSC-Regular;
      font-size: 1.35vw;
      color: #C2C2C2;
      letter-spacing: -0.63px;
    }

    /*selection-2*/
    .selection-2 {
      background: url('../assets/yddbj2@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-2 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
    }

    .selection-2 .tit {
      margin-bottom: 7.95vh;
    }
    
    .selection-2 .list {
      display: flex;
      align-items: center;
      flex-direction: column;
    }

    .selection-2 .list_div {
      display: flex;
      width: 48vw;
      cursor: pointer;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }
    .selection-2 .list-top {
      position: relative;
      width: 50%;
      height: 24vw;
    }
    .selection-2 .list-top img {
      position: absolute;
      left: 0;
      right: 0;
      top: 0;
      bottom: 0;
      margin: auto;
      width: 10.19vw;
      height: auto;
      z-index: 2;
    }
    .selection-2 .list-top .span-b {
      position: absolute;
      left: 0;
      bottom: 0;
      width: 100%;
      height: 100%;
      background: #1E1E1E;
      z-index: 1;
    }
    .selection-2 .list-top-c .span-b {
      position: absolute;
      left: 0;
      top: 0;
    }
    .selection-2 .list-bottom {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      width: 50%;
      height: 24vw;
      background: #FFF;
    }

    .selection-2 .list-bottom .img {
      width: 6.4vw;
      height: 6.4vw;
      margin: 0 auto 1.35vh;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }

    .selection-2 .list_div p {
      font-family: PingFangSC-Regular;
      font-size: 2.93vw;
      color: #505050;
      letter-spacing: -0.53px;   
    }
    
    /*selection-3*/
    .selection-3 {
      background: url('../assets/yddbj3@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    
    .selection-3 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
    }

    .selection-3 .tit {
      margin-bottom: 7.35vh;
    }

    .selection-3 .tit .p {
      color: #fff;
    }

    .selection-3 .list {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    .selection-3 .list .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 84.27vw;
      height: 13.33vw;
      margin: 0 auto 2.1vh;
      background: rgba(255, 255, 255, 0.24);
      cursor: pointer;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }
    .selection-3 .list .list_div img {
      width: 5.87vw;
      height: 5.87vw;
      margin-right: 6.4vw;
      margin-bottom: 0;
    }

    .selection-3 .list .list_div p {
      position: relative;
      width: 55.47vw;
      height: 5.87vw;
      margin-right: 2.45vw;
      font-family: PingFangSC-Regular;
      font-size: 1.25vw;
      color: #FFFFFF; 
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }

    .selection-3 .list .list_div p::after {
      content: '';
      position: absolute;
      right: 0;
      top: 5.87vw;
      width: 100%;
      height: 1px;
      opacity: 0.71;
      background: #D8D8D8;
    }
    
    .selection-3 .list .list_div:hover {
      background: rgba(255, 255, 255, 1);
    }
    .selection-3 .list .list_div:hover p {
      color: #000; 
    }

    .selection-3 .list .list_div:hover p::after {
      background: #000;
    }

    /*selection-4*/
    .selection-4 {
      background: url('../assets/yddbj4@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    
    .selection-4 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
    }

    .selection-4 .tit {
      margin-bottom: 10.49vh;
    }

    .selection-4 .tit .p {
      color: #fff;
    }

    .selection-4 .list-con {
      position: relative;
      display: flex;
      justify-content: center;
    }

    .selection-4 .left {
      position: absolute;
      right: 5.87vw;
      bottom: -15.59vw;
      margin-top: 2.96vh;
    }
    .selection-4 .left img {
      width: 35.2vw;
    }
    .selection-4 .right {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      position: relative;
      width: 65.07vw;
      height: 87.73vw;
      margin-right: 18.87vw;
      background: #FFFFFF;
    }
    .selection-4 .right .label {
      position: absolute;
      top: 22.9vw;
      right: -6.92vw;
      transform: rotate(-270deg);
      font-family: PingFangSC-Medium;
      font-size: 6.4vw;
      color: #C8C8C8;
      letter-spacing: -1.21px;    
    }

    .selection-4 .right p {
      margin-bottom: 4.17vh;
      padding-left: 5.07vw;
      font-family: PingFangSC-Regular;
      font-size: 1.25vw;
      color: #000000;
      letter-spacing: -0.58px;
    }
    .selection-4 .right p span {
      display: inline-block;
      width: 3.73vw;
      height: 3.73vw;
      margin-right: 1.3vw;
      border-radius: 50%;
      text-align: center;
      background: #E15100;
      font-family: PingFangSC-Regular;
      font-size: 2.67vw;
      color: #FFFFFF;
      line-height: 3.73vw;
    }

    /*selection-5*/
    .selection-5 {
      background: url('../assets/yddbj3@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    
    .selection-5 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
    }

    .selection-5 .tit {
      margin-bottom: 6.15vh;
    }

    .selection-5 .tit .p {
      color: #fff;
    }
    
    #swiper005 {
      width: 100vw;
      margin: 0 auto;
    }
    #swiper005 .swiper-slide {
      display: flex;
      align-items: center;
      justify-content: center;
    }
   
    .selection-5 .list {
      display: flex;
      justify-content: center;
    }

    .selection-5 .list_div {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      flex-direction: column;
      margin: 0 2.08vw;
    }
    .selection-5 .list_div p {
      margin-bottom: 1.85vh;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #FFFFFF;
      letter-spacing: -0.53px;
    }
    .selection-5 .list_div img {
      width: 36vw;
    }

    .selection-5 .yous-img {
      width: 88vw;
    }
    

    /*selection-7*/
    .selection-7 {
      background: #F9F9F9;
    }
    .selection-7 .cont {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      width: 100vw;
      height: 100%;
    }
    .selection-7 .tit {
      margin-bottom: 7.95vh;
    }
    .selection-7 .list {
      position: relative;
      display: flex;
      align-items: center;    
    }
    .selection-7 .list .next {
      display: flex;
      align-items: center;
      flex-direction: column;
      width: 7.2vw;
      height: 12vw;
      margin: 0 6.67vw 12vh 8.27vw;
    }
    .selection-7 .list .next span {
      width: 3.47vw;
      height: 3.47vw;
      margin-bottom: 1.5vh;
      border-radius: 100%;
      background: #E15100;
      line-height: 3.47vw;
      font-family: PingFangSC-Medium;
      font-size: 2.67vw;
      color: #FFFFFF;
      text-align: center;
    } 
    .selection-7 .list .next .s-next {
      transform: rotate(180deg);
    }
    .selection-7 .list .next img {
      width: 7.2vw;
      height: 5.87vw;
    }
    .selection-7 .list .next-c {
      position: absolute;
      right: 0;
      bottom: -33vw;
      flex-direction: inherit;
      width: 15vw;
    }
    .selection-7 .list .next-c img {
      transform: rotate(90deg);
    }
    .selection-7 .list_div {
      display: flex;
      align-items: center;
      flex-direction: column;
      height: 55.04vw;
    }
    .selection-7 .list_div img {
      width: 24vw;
      height: 42.67vw;
      margin-bottom: 0.9vh;
    }
    .selection-7 .list_div .img-con {
      display: flex;
      align-items: center;
      height: 25.52vw;
      margin-bottom: 0;
    }
    .selection-7 .list_div .ewm {
      width: 24vw;
      height: 24vw;
      margin-bottom: 0;
    }
    .selection-7 .list_div p {
      height: 8.53vw;
      font-family: PingFangSC-Regular;
      font-size: 2.93vw;
      text-align: center;
    }


    /*selection-8*/
    .selection-8 {

    }
    .selection-8 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 82.01vh;
      padding-left: 0;
      background: url('../assets/yddbj10@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-8 .tit {
      margin-bottom: 7.65vh;
    }

    .selection-8 .list {

    }
    .selection-8 .list_div {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      width: 79.2vw;
      height: 13.33vw;
      margin-bottom: 4.5vh;
      background: rgba(255, 255, 255, 0.56);
      cursor: pointer;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }
    .selection-8 .list_div span {
      display: inline-block;
      margin-right: 2.81vw;
      margin-left: 3.02vw;
      font-family: PingFangSC-Medium;
      font-size: 4.27vw;
      color: #001436;
      letter-spacing: -0.72px;
    }
    .selection-8 .list_div p {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #001436;
      letter-spacing: -0.53px;
    }
    
    .selection-8 .list_div:hover {
      background: #000;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }
    .selection-8 .list_div:hover p {
      color: #fff;
    }
    .selection-8 .list_div:hover span {
      color: #fff;
    }

    /*selection-6*/
    .selection-6 {
      background: url('../assets/yddbj9@2x.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-6 .cont {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      width: 100vw;
      height: 100%;
    }
    .selection-6 .tit {
      margin-bottom: 10.64vh;
    }
    .selection-6 .list {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
    }
    .selection-6 .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      margin: 0 0.4vw 8.55vh 0.4vw;
    }
    .selection-6 .list_div img {
      width: 45.07vw;
      height: 30.4vw;
      margin-bottom: 0.9vh;
    }
    .selection-6 .list_div h3 {
      display: block;
      width: 100%;
      text-align: left;
      margin-left: 2.55vw;
      margin-bottom: 1.11vh;
      font-family: PingFangSC-Medium;
      font-size: 3.73vw;
      color: #000000;
      letter-spacing: -0.77px;
    }
    .selection-6 .list_div p {
      display: block;
      width: 100%;
      text-align: left;
      margin-left: 2.55vw;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #505050;
      letter-spacing: -0.58px;
    }


    
  }

  @media screen and (min-width: 751px) {
      .selection-2 .list_div:hover .list-bottom .img {
        -webkit-transition: all 0.8s;
        transition: all 0.8s;
      }
      .selection-2 .list_div:hover .list-bottom .img_01 {
        background: url('../assets/pcyingiao_w@3x.svg') center center no-repeat;
        background-size: 100% 100%;
      }
      .selection-2 .list_div:hover .list-bottom .img_02 {
        background: url('../assets/pcqudo_w@3x.svg') center center no-repeat;
        background-size: 100% 100%;
      }
      .selection-2 .list_div:hover .list-bottom .img_03 {
        background: url('../assets/pcjiesuanz_w@3x.svg') center center no-repeat;
        background-size: 100% 100%;
      }
      .selection-2 .list_div:hover .list-bottom .img_04 {
        background: url('../assets/pcyionghutiy_w@3x.svg') center center no-repeat;
        background-size: 100% 100%;
      }
      .selection-2 .list_div:hover .list-bottom .img_05 {
        background: url('../assets/pcguangg_w@3x.svg') center center no-repeat;
        background-size: 100% 100%;
      }

      .selection-2 .list_div:hover {
        -webkit-transition: all 0.8s;
        transition: all 0.8s;
      }
      
      .selection-2 .list_div:hover .list-bottom {
        background: #E15100;
      }
      .selection-2 .list_div:hover .list-top .span-b {
        background: #E15100;
      }
      .selection-2 .list_div:hover p {
        color: #fff;
        -webkit-transition: all 0.8s;
        transition: all 0.8s;
      }

      .selection-3 .list .list_div {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        width: 7.97vw;
        height: 26.46vw;
        margin: 0 1.35vw;
        background: rgba(255, 255, 255, 0.24);
        cursor: pointer;
        -webkit-transition: all 0.8s;
        transition: all 0.8s;
      }
  }

  
</style>

