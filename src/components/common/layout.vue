<template>
  <div id="view-container">
    <div class="header">
        <div class="nav-list">
          <ul>
            <li>
              <a href="javascript:viod(0);">首页</a>
            </li>
            <li>
              <a href="javascript:viod(0);">数据市场</a>
            </li>
            <li>
              <a href="javascript:viod(0);">数据共享</a>
            </li>
            <li>
              <a href="javascript:viod(0);">个人中心</a>
            </li>
          </ul>
        </div>

        <div class="banner"> 
          <img src="../../assets/img/banner.jpg" alt="">
        </div>
    </div>
    <div class="content">

      <!-- 这是要做成 路由的区域 -->
      <div class="info-left">
        <ul class="info-list">
          <li class="info-list-item clearfix">
            <div class="info-content">
              <div class="info-content-left">
                <div class="info-img" >
                  <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1517767818040&di=ad8e9ca4c1b4ec96be5b13a9665795ec&imgtype=0&src=http%3A%2F%2Fk2.jsqq.net%2Fuploads%2Fallimg%2F1703%2F7_170331144403_4.jpg" alt="">
                </div> 
                <div class="info-text">
                  <h3>意大利2017年经济情况报告-全部数据</h3>
                  <p>意大利2017年金融、工业、旅游等主要经济类型各地金融工业旅游等主要经济类型各地</p>
                </div> 
              </div>
              <div class="info-content-right">
                <p>数据量: 200GB</p>
                <p>时间: 2018年1月29日</p>
              </div>
            </div>
          </li>

          <li class="info-list-item clearfix">
            <div class="info-content">
              <div class="info-content-left">
                <div class="info-img" >
                  <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1517767818040&di=ad8e9ca4c1b4ec96be5b13a9665795ec&imgtype=0&src=http%3A%2F%2Fk2.jsqq.net%2Fuploads%2Fallimg%2F1703%2F7_170331144403_4.jpg" alt="">
                </div> 
                <div class="info-text">
                  <h3>意大利2017年经济情况报告-全部数据</h3>
                  <p>意大利2017年金融、工业、旅游等主要经济类型各地金融工业旅游等主要经济类型各地</p>
                </div> 
              </div>
              <div class="info-content-right">
                <p>数据量: 200GB</p>
                <p>时间: 2018年1月29日</p>
              </div>
            </div>
          </li>

          <li class="info-list-item clearfix">
            <div class="info-content">
              <div class="info-content-left">
                <div class="info-img" >
                  <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1517767818040&di=ad8e9ca4c1b4ec96be5b13a9665795ec&imgtype=0&src=http%3A%2F%2Fk2.jsqq.net%2Fuploads%2Fallimg%2F1703%2F7_170331144403_4.jpg" alt="">
                </div> 
                <div class="info-text">
                  <h3>意大利2017年经济情况报告-全部数据</h3>
                  <p>意大利2017年金融、工业、旅游等主要经济类型各地金融工业旅游等主要经济类型各地</p>
                </div> 
              </div>
              <div class="info-content-right">
                <p>数据量: 200GB</p>
                <p>时间: 2018年1月29日</p>
              </div>
            </div>
          </li>

          <li class="info-list-item clearfix">
            <div class="info-content">
              <div class="info-content-left">
                <div class="info-img" >
                  <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1517767818040&di=ad8e9ca4c1b4ec96be5b13a9665795ec&imgtype=0&src=http%3A%2F%2Fk2.jsqq.net%2Fuploads%2Fallimg%2F1703%2F7_170331144403_4.jpg" alt="">
                </div> 
                <div class="info-text">
                  <h3>意大利2017年经济情况报告-全部数据</h3>
                  <p>意大利2017年金融、工业、旅游等主要经济类型各地金融工业旅游等主要经济类型各地</p>
                </div> 
              </div>
              <div class="info-content-right">
                <p>数据量: 200GB</p>
                <p>时间: 2018年1月29日</p>
              </div>
            </div>
          </li>

          <li class="info-list-item clearfix">
            <div class="info-content">
              <div class="info-content-left">
                <div class="info-img" >
                  <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1517767818040&di=ad8e9ca4c1b4ec96be5b13a9665795ec&imgtype=0&src=http%3A%2F%2Fk2.jsqq.net%2Fuploads%2Fallimg%2F1703%2F7_170331144403_4.jpg" alt="">
                </div> 
                <div class="info-text">
                  <h3>意大利2017年经济情况报告-全部数据</h3>
                  <p>意大利2017年金融、工业、旅游等主要经济类型各地金融工业旅游等主要经济类型各地</p>
                </div> 
              </div>
              <div class="info-content-right">
                <p>数据量: 200GB</p>
                <p>时间: 2018年1月29日</p>
              </div>
            </div>
          </li>

        </ul>
        <!-- 分页组件 -->
        <div class="page-component">
          <el-pagination
            background
            layout="prev, pager, next"
            :total="1000">
          </el-pagination>
        </div>
        
      </div>
      <div class="info-right">
        <div class="info-right-top">
          <h3>数据获取</h3>
          <ul>
            <li>注册</li>
            <li>申请</li>
            <li>批准</li>
            <li>获取</li>
          </ul>
        </div>
        <div class="info-right-bot">
          <h3>数据共享</h3>
          <ul>
            <li>登录</li>
            <li>描述</li>
            <li>发布</li>
            <li>等待获取申请</li>
          </ul>
        </div>
      </div>
      <!-- 这是要做成 路由的区域 end -->

    </div>
    <div class="footer">
      <p>copyright @2018 洛阳师范学院</p>
    </div>
    
  </div>
</template>
<script>
export default {
  name: "Layout",
  data() {
    return {};
  },
  created() {},
  components: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
#view-container {
  height: 100%;
  display: flex;
  width: 1000px;
  justify-content: center;
  flex-direction: column;
  margin: 0 auto;

  // min-height: 900px;

  .header {
    // background-color: #fff;
    // flex: 4;
    height: 170px;
    .nav-list {
      height: 50px;
      min-height: 50px;
      line-height: 50px;
      float: right;

      ul {
        li{
          float: left;
          text-align: center;
          a{
            display: block;
            height: 50px;
            font-size: 16px;
            font-weight: 700;
            line-height: 50px;
            padding: 0 20px;
          }
        }
      }
    }
    .banner {
      height: 120px;
      width: 100%;
      overflow: hidden;
      img {
        width: 100%;
      }
    }
  }
  .footer {
    // flex: 1;
    height: 50px;
    // background-color: #fff;
    text-align: center;
    p {
      font-size: 14px;
      color: #999;
      line-height: 50px;
    }
  }
  .content {
    // width: 1000px;
    display: flex;
    flex: 1;
    // background-color: #fff;
    border-bottom: 1px dashed #ccc;
    min-height: 500px;

    .info-left {
      flex: 4;
      // background-color: red;

      .info-list {
        padding: 10px 0px;
        .info-list-item {
          padding: 10px 0;

          border-bottom: 1px dashed #ccc;
          .info-content-left {
            .info-img {
              width: 60px;
              float: left;
              img {
                width: 100%;
              }
            }

            .info-text {
              padding: 8px 14px;
              float: left;
              width: 480px;
              

              h3 {
                font-size: 18px;
                font-weight: 700;
                color: rgb(49, 49, 49);
              }
              p {
                margin-top: 12px;
                font-size: 14px;
                color: rgb(151, 151, 151);
                // 省略号
                width: 480px;
              text-overflow: ellipsis;
              overflow: hidden;
              white-space: nowrap;
              }
            }
          }
          .info-content-right {
            float: left;
            padding: 10px 40px;

            border-left: 1px dashed rgb(161, 161, 161);
            p {
              font-size: 12px;
            }
            p + p {
              margin-top: 10px;
            }
          }
        }

        .info-list-item:first-child {
          border-top: 1px dashed #ccc;
        }
      }

      .page-component {
        float: right;
      }
    }
    .info-right {
      flex: 1;
      // background-color: rgb(185, 185, 185);
      padding-top: 10px;
      padding-left: 10px;
      .info-right-top,
      .info-right-bot {
        height: 228px;
        border: 1px solid #ccc;
        text-align: center;

        h3{
          font-size: 16px;
          font-weight: 700;
          height: 50px;
          line-height: 50px;
        }
        ul{
          li{
            font-size: 14px;
            height: 40px;
            line-height: 40px;
          }
        }

      }
      .info-right-top {
        
      }
      .info-right-bot {
        margin-top: 10px;
       
      }
    }
  }
}
</style>
