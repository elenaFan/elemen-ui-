<template>
  <div id="app">
    <div class="all" id="box">
      <div class="screen">
        <el-carousel
          :interval="5000"
          arrow="always"
          @change="changeNum()"
        >
          <el-carousel-item>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">1111王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
          </el-carousel-item>
          <!-- <li><img src="./assets/02.jpg" width="500" height="200"/></li> -->
          <el-carousel-item>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">2222222222222王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
          </el-carousel-item>
          <el-carousel-item>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">33王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
          </el-carousel-item>
          <el-carousel-item>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">44444王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">4444王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
          </el-carousel-item>
          <el-carousel-item>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">555王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
            <div class="slide-item">
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
              <span class="detail-item">
                <i class="name">王二的合漏了.pp</i>
                <i class="ivu-icon ivu-icon-ios-warning"></i>
                <i class="operation">删除</i>
                <i class="operation">新增</i>
              </span>
            </div>
          </el-carousel-item>
        </el-carousel>
        <!-- <ol>
          <li class="current">1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
        </ol> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  methods: {
    changeNum(a) {
      console.log(a);
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
/* .el-carousel__arrow {
  top: 30% !important;
} */
/* .el-carousel__item h3 {
  color: #475669;
  font-size: 18px;
  opacity: 0.75;
  line-height: 300px;
  margin: 0;
} */
.el-icon-arrow-left,
.el-icon-arrow-right {
  margin: 0px 10px;
}
/* .el-carousel__item:nth-child(2n) {
  background-color:#fff;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #fff;
} */
* {
  padding: 0;
  margin: 0;
  list-style: none;
  border: 0;
}
.detail-item {
  display: inline-block;
  margin-left: 30px;
  height: 21px;
  /* vertical-align: bottom; */
  line-height: 21px;
}
.slide-item {
  margin-top: 15px;
  /* position: relative; */
}
i {
  float: left;
  font-style: normal;
  margin: 0px 3px;
}
.operation {
  font-size: 10px;
  /* float: left; */
}
.name {
  /* float: left; */
  margin: 0px 3px;
  display: inline-block;
  width: 110px;
  white-space: nowrap;
  overflow: hidden;
}
.ivu-icon {
  width: 15px;
  height: 15px;
  display: inline-block;
  font-size: 17px;
  color: gold;
  /* line-height:; */
}
#app {
  background-color:#eee;
  height: 700px;
}

/* .el-carousel__indicators {
  border-bottom: 78px;
} */
.el-carousel__indicators{
  background-color: aqua !important;
  z-index: 999 !important;
  color:red !important;
}
.el-carousel__container{
  height: 180px !important;
}
.el-carousel__button {
  background-color: black;
}
.all {
  width: 900px;
  height: 180px;
  /* padding: 7px; */
  border: 1px solid #ccc;
  margin: 100px auto;
  position: relative;
  background-color: aquamarine;
}

.screen {
  width: 900px;
  height: 180px;
  overflow: hidden;
  position: relative;
}

.screen el-carousel-item {
  width: 900px;
  height: 180px;
  overflow: hidden;
  float: left;
  font-size: 14px;
}

.screen el-carousel {
  position: absolute;
  left: 0;
  top: 0px;
  width: 5400px;
}
/* .all ol {
  position: absolute;
  right: 50%;
  transform:translateX(50%);
  bottom: 10px;
  line-height: 20px;
  text-align: center;
  z-index: 999;
}

.all ol li {
  float: left;
  width: 10px;
  height: 10px;
  background: #fff;
  border: 1px solid #ccc;
  border-radius: 50%;
  margin-left: 10px;
  cursor: pointer;
}

.all ol li.current {
  background: yellow;
} */

</style>
