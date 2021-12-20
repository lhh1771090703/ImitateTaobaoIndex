<template>
  <div>
    <!-- 头部导航 -->
    <div id="headerMessage" class="clearfix layer">
      <ul class="fl">
        <li>
          <span>中国大陆</span>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
        <li class="mr7">
          <a href="#" class="login mr7">亲，请登录</a>
          <a href="#">免费注册</a>
        </li>
        <li><a href="#">手机逛淘宝</a></li>
      </ul>
      <ul class="fr">
        <li>
          <a href="#">我的淘宝</a>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
        <li>
          <!-- 购物车图标 -->
          <span class="iconfont mr5 c4">&#xe60d;</span>
          <a href="#">购物车</a>
          <strong>0</strong>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
        <li>
          <a href="#" class="store">
            <span class="iconfont mr5">&#xe91a;</span>收藏夹
          </a>
          <span class="iconfont">&#xe626;</span>
        </li>
        <li>
          <a href="#"> 商品分类 </a>
        </li>
        <li class="line">|</li>
        <li>
          <a href="#">千牛卖家中心</a>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
        <li>
          <a href="#">联系客服</a>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
        <li>
          <span class="iconfont c4 mr5">&#xe790;</span>
          <a href="#">网站导航</a>
          <span class="iconfont arrow">&#xe626;</span>
        </li>
      </ul>
    </div>
    <!-- 头部广告导航 -->
    <div id="headerAd">
      <div class="layer clearfix">
        <!-- logo图片 -->
        <a href="#" class="fl go"
          ><img src="@/assets/imgs/Jdlogo.png" alt="logo"
        /></a>
        <ul class="fr">
          <li class="item1">
            <a href="#" class="fr">
              <img src="@/assets/imgs/01.jpg" alt="" />
            </a>
            <h3><a href="#">电视会场</a></h3>
            <p><a href="#">最高峰2000</a></p>
          </li>
          <li class="item2">
            <a href="#" class="fr">
              <img src="@/assets/imgs/02.jpg" alt="" />
            </a>
            <h3><a href="#">厨房电器</a></h3>
            <p><a href="#">抢大额券</a></p>
          </li>
          <li class="item3">
            <a href="#" class="fr">
              <img src="@/assets/imgs/03.jpg" alt="" />
            </a>
            <h3><a href="#">超值囤货</a></h3>
            <p><a href="#">1元抢百券</a></p>
          </li>
          <li class="item4">
            <a href="#" class="fr">
              <img src="@/assets/imgs/04.png" alt="" />
            </a>
            <h3><a href="#">全球冰洗</a></h3>
            <p><a href="#">三门冰箱888</a></p>
          </li>
          <li class="item5">
            <a href="#" class="fr">
              <img src="@/assets/imgs/05.jpg" alt="" />
            </a>
            <h3><a href="#">潮酷数码</a></h3>
            <p><a href="#">大牌爆款直降</a></p>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <!-- 头部搜索框 -->
  <div id="headerSearch">
    <div class="clearfix layer">
      <h1 class="fl"><a href="">淘宝网</a></h1>
      <div class="code fr">
        <span class="iconfont close">&#xeb6a;</span>
        <span class="c5">手机淘宝</span>
        <img src="@/assets/imgs/qrcode.jpg" alt="" />
      </div>
      <!-- 中间搜索框 -->
      <div class="search">
        <ul class="searchTab clearfix">
          <li class="active">宝贝</li>
          <li>天猫</li>
          <li>店铺</li>
        </ul>
        <div class="searchContent clearfix">
          <form action="#">
            <div class="searchBox fl">
              <input type="text" />
              <div class="placeholder">
                <i class="iconfont">&#xe86e;</i>
                <span>网红裤腰带 洋气 国际范 9.9包邮</span>
              </div>
              <span class="iconfont camera">&#xe872;</span>
            </div>
            <div class="btn fl">
              <button type="submit">搜索</button>
            </div>
          </form>
        </div>
        <!-- 中间底部热词 -->
        <div class="hotKey">
          <a href="#" class="c5">积木</a>
          <a href="#">网线</a>
          <a href="#" class="c5">爬行垫</a>
          <a href="#">时尚连衣裙</a>
          <a href="#">男士T恤</a>
          <a href="#" class="c5">时尚休闲裤</a>
          <a href="#">粽子</a>
          <a href="#">沙发</a>
          <a href="#">风扇</a>
          <a href="#">定制窗帘</a>
          <a href="#">男士内裤</a>
          <a href="#">凉席三件套</a>
          <a href="#">办公桌</a>
        </div>
      </div>
    </div>
  </div>
  <!-- 导航内容 -->
  <div id="nav" class="clearfix layer">
    <h2 class="fl">主题市场</h2>
    <ul>
      <li class="size"><a href="#">天猫</a></li>
      <li class="size"><a href="#">聚划算</a></li>
      <li class="size"><a href="#">天猫超市</a></li>
      <li class="line">|</li>
      <li><a href="#">淘抢购</a></li>
      <li><a href="#">电器城</a></li>
      <li><a href="#">司法拍卖</a></li>
      <li><a href="#">淘宝精选</a></li>
      <li><a href="#">兴农扶贫</a></li>
      <li class="line">|</li>
      <li><a href="#">飞猪旅行</a></li>
      <li><a href="#">智能生活</a></li>
      <li><a href="#">苏宁易购</a></li>
    </ul>
  </div>
  <!-- 首屏内容 -->
  <div id="firstGreen" class="layer clearfix">
    <!-- 左边内容 -->
    <div class="firstLeft fl">
      <!-- 侧边导航 -->
      <div class="sdieNav fl">
        <ul>
          <li>
            <a href="#">女装</a> / <a href="#">男装</a> / <a href="#">内衣</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">女鞋</a> / <a href="#">男鞋</a> / <a href="#">箱包</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">母婴</a> / <a href="#">童装</a> / <a href="#">玩具</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">家居</a> / <a href="#">户外运动</a> /
            <span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">美妆</a> / <a href="#">彩妆</a> / <a href="#">个护</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">女装</a> / <a href="#">男装</a> / <a href="#">内衣</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">手机</a> / <a href="#">数码</a> / <a href="#">企业</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">大家电</a> / <a href="#">生活电器</a> /
            <span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">零食</a> / <a href="#">生鲜</a> / <a href="#">茶酒</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">厨具</a> / <a href="#">收纳</a> / <a href="#">清洁</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">家访</a> / <a href="#">家饰</a> / <a href="#">鲜花</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">图文音像</a> / <a href="#">文具</a> /
            <span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">医药保健</a> / <a href="#">进口</a> /
            <span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">汽车</a> / <a href="#">二手车</a> / <a href="#">用品</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">房产</a> / <a href="#">装修家具</a> /
            <a href="#">建材</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
          <li>
            <a href="#">手表</a> / <a href="#">眼镜</a> /
            <a href="#">珠宝首饰</a
            ><span class="iconfont icon-zuojiantou-cu fr"></span>
          </li>
        </ul>
      </div>
      <!-- 图片1容器 -->
      <div class="img1Box fr">
        <div class="pic fl">
          <div class="img">
            <a href="#"><img src="@/assets/imgs/lunbotu.jpg" alt="" /></a>
          </div>
          <button class="iconfont leftBtn icon-xiangzuojiantou"></button>
          <button class="iconfont rightBtn icon-zuojiantou-cu"></button>
          <div class="circle">
            <span class="active"></span><span></span><span></span><span></span
            ><span></span>
          </div>
        </div>
        <div class="ad fr">
          <a href="#"
            ><img src="@/assets/imgs/Adr.jpg" alt="" class="adImg"
          /></a>
        </div>
      </div>
      <!-- 图片2容器 -->
      <div class="img2Box fr">
        <div class="picTitle">
          <span class="fl titleLf">理想生活上天猫</span>
          <span class="fr titleRf">1/5</span>
        </div>
        <div class="barImg clearfix">
          <a href="#"><img src="@/assets/imgs/轮播图01.jpg" alt="" /></a>
          <a href="#"><img src="@/assets/imgs/轮播图02.jpg" alt="" /></a>
          <button class="iconfont icon-xiangzuojiantou lBtn"></button>
          <button class="iconfont icon-zuojiantou-cu rBtn"></button>
        </div>
      </div>
      <!-- 淘宝头条 -->
      <div class="news fl">
        <div class="news_next">
          <strong>&emsp;班级： <span>动画4班 📖</span></strong>

          <strong>&emsp;年级：<span>19级 🤷‍♂️</span></strong>

          <strong>&emsp;姓名：<span>罗毫毫 👨‍💻</span></strong>
        </div>
      </div>
    </div>
    <!-- 右边内容 -->
    <div class="firstRight fr">
      <div class="rightCenter clearfix">
        <a href="#">注册</a>
        <a href="#">登录</a>
        <a href="#">开店</a>
        <div class="iconHi">
          <img src="@/assets/imgs/ICON.jpg" alt="" /> <span>Hi! 你好</span>
        </div>
        <a href="#" class="guangbao">
          <img src="@/assets/imgs/live.png" alt=""
        /></a>
        <!-- 底部广告标题 -->
      </div>
      <div class="bottomTitle">
        <div class="bottomBar">
          <span>公告</span><span> 新鲜事儿都在这里～</span>
        </div>
        <div class="bottomAd">
          <ul>
            <li>
              <a href="#">规则</a><a href="#">淘宝网市场管理与违规处理规范</a>
            </li>
            <li>
              <a href="#">热点</a
              ><a href="#">关于推进“清朗”账号乱象专项整治的通知</a>
            </li>
            <li>
              <a href="#">热点</a
              ><a href="#">《淘宝平台违禁信息管理规则》规则变更通知</a>
            </li>
          </ul>
          <div class="iconBottom">
            <a href="#"
              ><i class="iconfont numOne">&#xe9a1;</i><span>收藏的宝贝</span></a
            >
            <a href="#"
              ><i class="iconfont">&#xe63c;</i><span>买过的店铺</span></a
            >
            <a href="#"
              ><i class="iconfont">&#xe895;</i><span>收藏的店铺</span></a
            >
            <a href="#"
              ><i class="iconfont">&#xe755;</i><span>我的足迹</span></a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- 有好货与爱逛街 -->
  <div id="layer"></div>
  <!-- 右侧固定导航 -->
  <div id="tool"></div>
</template>

<script>
export default {
  name: 'VueCenter',
}
</script>

<style lang="less" scoped>
// 设置头部css
#headerMessage {
  span {
    font-size: 12px;
  }
  .arrow {
    margin-left: 7px;
  }
  ul {
    .line {
      font-size: 12px;
      color: #ddd;
      padding: 0 5px;
    }
    li {
      float: left;
      line-height: 35px;
      padding: 0 6px;
      font-size: 0;
      .store {
        color: #9c9c9c;
      }
      strong {
        font-size: 12px;
        color: #f33e00;
      }
      .login {
        color: #f22e00;
      }
      a {
        font-size: 12px;
        color: #6c6c6c;
      }
      a:hover {
        color: #f40;
      }
    }
  }
}
// 头部广告css
#headerAd {
  background-color: #f12f04;
  .go {
    display: block;
    padding: 10px 10px 10px 15px;
  }
  ul {
    margin-top: 13px;
    li {
      float: left;
      width: 209px;
      height: 75px;
      margin-right: 10px;
      padding: 12px 15px 0 15px;
      box-sizing: border-box;
      a {
        color: #fff;
        display: block;
      }
      h3 {
        font-size: 20px;
        line-height: 28px;
      }
      p {
        font-size: 14px;
        line-height: 20px;
      }
      img {
        width: 52px;
        height: 52px;
        border-radius: 5px;
      }
    }
    .item5 {
      margin-right: 0;
    }
  }
}
// 头部搜索
#headerSearch {
  background-color: #fff;
  padding: 24px 0 10px 0;
  h1 {
    a {
      display: block;
      width: 190px;
      height: 58px;
      background: url('./tbbg.png') center no-repeat;
      text-indent: -9999px;
      overflow: hidden;
      margin-top: 8px;
    }
  }
  .close {
    position: absolute;
    left: -16px;
    top: -1px;
    width: 14px;
    height: 14px;
    font-size: 14px;
    line-height: 14px;
    border: solid 1px #eee;
    color: #ddd;
    cursor: pointer;
  }
  .code {
    width: 72px;
    height: 86px;
    border: solid 1px #eee;
    position: relative;
    margin-right: 110px;
    text-align: center;
    img {
      width: 62px;
      height: 62px;
    }
  }
  .search {
    width: 630px;
    margin: 0 auto;
  }
  .searchTab {
    height: 22px;
    padding-left: 17px;
    li {
      float: left;
      width: 36px;
      line-height: 22px;
      margin-left: 4px;
      text-align: center;
      color: #f40;
      cursor: pointer;
      &:hover {
        background-color: #ffeee5;
      }
    }
    .active {
      color: #fff;
      font-weight: bold;
      border-radius: 6px 6px 0 0;
      // 设置线性渐变
      background-image: linear-gradient(to right, #ff9000, #ff5000);
      &:hover {
        background-color: red;
      }
    }
  }
  .searchContent {
    height: 40px;
    button {
      width: 74px;
      height: 40px;
      text-align: center;
      font-size: 18px;
      color: #fff;
      border-radius: 0 20px 20px 0;
      border: none;
      line-height: 40px;
      background-image: linear-gradient(to right, #ff9000, #ff5000);
    }
  }
  .searchBox {
    width: 554px;
    height: 40px;
    box-sizing: border-box;
    border: solid 2px #ff5000;
    border-right: none;
    border-radius: 20px 0 0 20px;
    overflow: hidden;
    position: relative;
    input {
      width: 490px;
      height: 36px;
      line-height: 36px;
      outline: none;
      border: none;
      text-indent: 10px;
      position: absolute;
      z-index: 2;
      background-color: transparent;
    }
    .placeholder {
      position: absolute;
      top: 6px;
      left: 14px;
      i {
        vertical-align: middle;
      }
      span {
        color: #9c9c9c;
        vertical-align: middle;
      }
    }
    .camera {
      position: absolute;
      right: 20px;
      font-size: 28px;
      color: #9c9c9c;
      top: -3px;
      cursor: pointer;
    }
  }
  .hotKey {
    height: 25px;
    line-height: 25px;

    a {
      color: #3c3c3c;
      padding: 0 1.8px;
      &:hover {
        color: #f50;
      }
    }
    .c5 {
      color: #f50;
    }
  }
}
// 导航内容
#nav {
  h2 {
    width: 190px;
    height: 30px;
    line-height: 30px;
    font-size: 16px;
    color: #fff;
    text-align: center;
    background-color: #f50;
  }
  ul {
    // width: 1000px;
    // width: calc(100% - 190px);
    margin-left: 190px;
    height: 30px;
    background-image: linear-gradient(to right, #ff9000, #ff5000);
    li {
      float: left;
      line-height: 30px;
      margin: 0 7px;
      font-size: 14px;
      color: #fff;
      position: relative;
      padding: 0 5px;
      a {
        color: #fff;
        font-weight: bold;
      }
      &.size {
        font-size: 16px;
      }
      &.line {
        margin: 0;
        padding: 0;
      }
      &:hover::before {
        content: '';
        position: absolute;
        width: 23px;
        height: 13px;
        background: url('./gaitubao_01_gif.gif') no-repeat;
        background-size: cover;
        top: -13px;
        border-radius: 22px 22px 0 0;
        overflow: hidden;
        left: 50%;
        margin-left: -12.5px;
      }
    }
  }
}
//首屏内容,侧边导航，图片容器，淘宝头条
#firstGreen {
  .firstLeft {
    width: 890px;
    .sdieNav {
      width: 190px;
      height: 522px;
      background-color: #fff;
      border: 1px solid #ff5000;
      box-sizing: border-box;
      border-top: none;
      padding-top: 5px;
      li {
        height: 32px;
        line-height: 32px;
        padding-left: 25px;
        color: #999;
        &:hover {
          background-color: #ffe4dc;
          transition: background-color 0.3s;
          color: #f50;
          a {
            color: #f50;
            &:hover {
              text-decoration: underline;
            }
          }
        }
        a {
          font-size: 14px;
          color: #666;
        }
        span {
          font-size: 12px;
          margin-right: 5px;
        }
      }
    }
    .img1Box {
      width: 690px;
      height: 282px;
      top: 0;
      margin-top: 10px;
      .pic {
        position: relative;
        &:hover button {
          display: block;
        }
        .circle {
          position: absolute;
          bottom: 15px;
          left: 50%;
          background-color: rgba(255, 255, 255, 0.3);
          border-radius: 10px;
          padding: 3px 0;
          font-size: 0;
          margin-left: -35px;
          span {
            display: inline-block;
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background-color: #fff;
            margin: 0 3px;
            cursor: pointer;
            &.active {
              background-color: #ff5000;
            }
          }
        }
        button {
          width: 20px;
          height: 30px;
          line-height: 30px;
          color: #fff;
          cursor: pointer;
          border: none;
          background-color: rgba(0, 0, 0, 0.3);
          position: absolute;
          top: 50%;
          margin-top: -15px;
          display: none;
          &:hover {
            transition: all 0.3s;
            background-color: rgba(0, 0, 0, 0.6);
          }
        }
        .leftBtn {
          border-radius: 0 15px 15px 0;
          left: 0;
        }
        .rightBtn {
          right: 0;
          border-radius: 15px 0 0 15px;
        }
        .img {
          width: 520px;
          position: relative;
        }
      }
      .adImg {
        width: 160px;
        height: 280px;
      }
    }
    .img2Box {
      width: 690px;
      height: 230px;
      margin-top: 10px;
      .picTitle {
        height: 20px;
        background: url('./下载.jpg') no-repeat;
        background-position-x: 10px;
        line-height: 20px;
        .titleLf {
          margin-left: 97px;
          color: #999999;
        }
        .titleRf {
          margin-right: 15px;
        }
      }
      .barImg {
        position: relative;
        height: 209.99px;
        padding: 10px 12px;
        &:hover {
          button {
            display: block;
          }
        }
        button {
          width: 20px;
          height: 30px;
          line-height: 30px;
          color: #fff;
          cursor: pointer;
          border: none;
          background-color: rgba(0, 0, 0, 0.3);
          position: absolute;
          margin-top: -14px;
          display: none;
          &:hover {
            transition: all 0.3s;
            background-color: rgba(0, 0, 0, 0.6);
          }
        }
        .lBtn {
          left: 0;
          top: 50%;
          transform: translateY(-50%);
          border-radius: 0 15px 15px 0;
        }
        .rBtn {
          right: 0;
          top: 50%;
          transform: translateY(-50%);
          border-radius: 15px 0 0 15px;
        }
        a {
          img {
            margin: 0 6px;
            width: 320px;
            height: 190px;
            overflow: hidden;
            border-radius: 20px;
          }
        }
      }
    }
    // 淘宝头条
    .news {
      .news_next {
        height: 100px;
        strong {
          height: 33.33%;
          display: block;
          color: #3c3c3c;
          text-shadow: 1px 1px 1px green;
          font-size: 20px;
        }
      }
      margin-top: 10px;
      width: 1189.99px;
      height: 100px;
      background-color: #f7efef;
    }
  }
  //右边导航css
  .firstRight {
    width: 290px;
    background-color: rgb(240, 235, 235);
    .rightCenter {
      position: relative;
      top: 100px;
      height: 31.99px;
      line-height: 31.99px;
      padding-left: 14px;
      margin: 0 auto;
      width: 289.99px;

      .guangbao {
        margin-top: 0px;
        background-color: #f3f3f3;
        display: inline-block;
        img {
          position: absolute;
          left: 14px;
          width: 255.94px;
          margin-top: 10px;
        }
      }
      .iconHi {
        position: absolute;
        top: -90px;
        left: 50%;
        transform: translateX(-25px);
        font-size: 0;
        text-align: center;
        cursor: pointer;
        img {
          border-radius: 50%;
        }
        span {
          display: block;
          font-size: 12px;
          &:hover {
            color: #f22e00;
          }
        }
      }
      a {
        display: block;
        width: 80.99px;
        height: 31.99px;
        font-size: 12px;
        color: #fff;
        margin-right: 6px;
        background-color: #ff5000;
        text-align: center;
        float: left;
        border-radius: 5px;
      }
    }
    .bottomTitle {
      padding-top: 220px;
      .bottomBar {
        width: 431px;
        margin-top: 45.4px;
        & :first-child {
          height: 16px;
          font-size: 12px;
          line-height: 16px;
          font-weight: 700;
          padding-left: 14px;
        }
        & :last-child {
          margin-left: 6px;
          height: 16px;
          font-size: 12px;
          line-height: 16px;
        }
      }
      .bottomAd {
        ul {
          padding: 15px 0 0 16px;
          box-sizing: border-box;
          li {
            position: relative;
            margin-bottom: 22px;
            text-overflow: ellipsis;
            overflow: hidden;
            white-space: nowrap;
            & :first-child {
              color: #ff5000;
              position: absolute;
              left: 0;
              display: inline-block;
              background-color: #ffaeae33;
              width: 32px;
              height: 18px;
              text-align: center;
            }
            & :last-child {
              color: #000;
              margin-left: 35px;
            }
          }
        }
        .iconBottom {
          margin: 55px 0 0 0;
          a {
            position: relative;
            display: inline-block;
            height: 50px;
            width: calc(100% / 4);
            margin: 0;
            background-color: transparent;
            .numOne {
              color: rgba(60, 60, 60, 0.6);
            }
            i {
              font-size: 24px;
              display: block;
              position: static;
              text-align: center;
              color: #3c3c3c;
              height: auto;
              background-color: transparent;
              &:hover {
                color: #ff4400;
              }
            }
            span {
              padding: 0;
              margin: 0;
              display: block;
              text-align: center;
              color: #333333;
            }
          }
        }
      }
    }
  }
}
</style>
