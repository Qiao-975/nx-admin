<template>
  <div class="project-archives">
    <div class="layui-row navtitle">
      <div class="title2">项目档案</div>
      <button type="button" class="layui-btn layui-btn-sm layui-btn-primary backto">
        <i class="layui-icon">&#xe603;</i> 返回
      </button>
    </div>
    <el-breadcrumb separator="/" class="currentposition">
      <el-breadcrumb-item>总行</el-breadcrumb-item>
      <el-breadcrumb-item>信息科技部</el-breadcrumb-item>
      <el-breadcrumb-item>开发四室</el-breadcrumb-item>
    </el-breadcrumb>
    <div class="layui-row topsection">
      <div class="layui-col-md4 imgsection">
        <div class="imgbox">
          <img src="../../assets/images/img1.png" alt />
        </div>
        <div class="topleft">
          <div class="row1">
            <p>
              项目年度
              <span>2020</span>
            </p>
            <p>
              优先级
              <span>一般</span>
            </p>
            <p>
              需求总数
              <span>186</span>
            </p>
          </div>
          <div class="row2">
            <p>
              项目工期
              <span>12个月</span>
            </p>
            <p>
              后评价
              <span>是</span>
            </p>
            <p>
              项目金额
              <span>****</span>
            </p>
          </div>
        </div>
      </div>
      <div class="layui-col-md8 rightr">
        <div class="layui-row">
          <div class="layui-col-md7 title1box">
            <div class="title1row">
              <p class="title1">新一代数字化信贷系统项目</p>
              <p class="projectId">
                项目编号：
                <span>2020001320002</span>
              </p>
            </div>
            <div class="description2">
              <p class="title4 title41">
                项目类型：
                <span>应用开发类</span>
              </p>
              <p class="title4 title41">
                实施方式：
                <span>新建</span>
              </p>
              <p class="title4 title42">
                项目负责人：
                <span>总行/信息科技部/韩博</span>
              </p>
            </div>
          </div>
          <div class="layui-col-md5 flagstar">
            <div class="block1">
              <div class="flag">
                <i class="layui-icon layui-icon-flag"></i>
              </div>
              <div class="title3">项目进度</div>
              <div class="description">实施中</div>
            </div>
            <div class="block1">
              <div class="flag">
                <i class="layui-icon layui-icon-form"></i>
              </div>
              <div class="title3">项目质量指数</div>
              <div class="description">4.8</div>
            </div>
            <div class="block1">
              <div class="star">
                <i class="layui-icon layui-icon-rate-solid" />
                <i class="layui-icon layui-icon-rate-solid" />
                <i class="layui-icon layui-icon-rate-solid" />
                <i class="layui-icon layui-icon-rate-solid" />
                <i class="layui-icon layui-icon-rate-solid" />
              </div>
              <div class="title3">4项目评价星级</div>
              <div class="description">五星级</div>
            </div>
          </div>
        </div>
        <div class="tabcontainer">
          <el-tabs v-model="activeName" :stretch="true" @tab-click="handleClick">
            <el-tab-pane
              label="项目概况"
              name="gaikuang"
            >新建全新、独立的数字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。重新设计业务管理模块，实现圈子内的业务处理模式。</el-tab-pane>
            <el-tab-pane name="jihua">
              <span slot="label">
                <span class="layui-badge-dot"></span> 项目计划
              </span>
              项目计划、项目计划项目计划，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="xuqiu">
              <span slot="label">
                <span class="layui-badge-dot"></span> 需求管理
              </span>
              需求管理、需求管理需求管理统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="lixiang">
              <span slot="label">
                <span class="layui-badge-dot"></span> 立项
              </span>
              立项立项、立项立项字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="shangwu">
              <span slot="label">
                <span class="layui-badge-dot"></span> 商务
              </span>
              商务商务、独立的数字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="ceshi">
              <span slot="label">
                <span class="layui-badge-dot"></span> 开发测试
              </span>
              开发测试、开发测试化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="touchan">
              <span slot="label">
                <span class="layui-badge-dot"></span> 投产
              </span>
              投产投产新、独立的数字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="yanshou">
              <span slot="label">
                <span class="layui-badge-dot"></span> 验收
              </span>
              验收验收、独立的数字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
            <el-tab-pane name="houpingjia">
              <span slot="label">
                <span class="layui-badge-dot"></span> 后评价
              </span>
              后评价后评价后评价、后评价后评价后评系统，将后评价后评价后评信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。
            </el-tab-pane>
          </el-tabs>
        </div>
      </div>
    </div>
    <div class="layui-row danganqita">
      <div class="layui-col-md7 dangan">
        <div class="dangancon">
          <div class="layui-card">
            <div class="layui-card-header">卡片面板</div>
            <div class="layui-card-body">
              卡片式面板面板通常用于非白色背景色的主体内
              <br>从而映衬出边框投影
            </div>
          </div>
        </div>
      </div>
      <div class="layui-col-md5 qita">
        <div class="qitacon">
          <div class="layui-card">
            <div class="layui-card-header">卡片面板</div>
            <div class="layui-card-body">
              卡片式面板面板通常用于非白色背景色的主体内
              <br>从而映衬出边框投影
              <div id="text1" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'project-archives',
  data() {
    return {
      activeName: 'gaikuang'
    }
  },
  mounted: function() {
    // eslint-disable-next-line no-undef
    layui.use(['rate'], function() {
      // eslint-disable-next-line no-undef
      var rate = layui.rate
      rate.render({
        elem: '#test1', value: 5, readonly: true
      })
    })
  },
  methods: {
    handleClick(tab, event) {
      console.log(tab, event)
    }
  }
}
</script>
<style lang="scss" scoped>
@import "../../scss/color.scss";
.project-archives {
  width: 100%;
  height: 100%;
  background: $mbgccolor1;
  .navtitle {
    overflow: hidden;
    border-bottom: $mborderbottom;
    line-height: 40px;
    padding: 0 10px;
    .title2 {
      float: left;
    }
    .title2::before {
      content: "";
      display: inline-block;
      width: 4px;
      height: 14px;
      background: $mcolor1;
      margin-right: 5px;
    }
    .backto {
      float: right;
      margin-top: 5px !important;
    }
  }
  .currentposition {
    line-height: 40px;
    padding-left: 20px;
  }

  .topsection {
    width: 100%;
    padding: 0 20px;
    .imgsection {
      padding-right: 20px;
      .imgbox {
        width: 100%;
        height: auto;
        img {
          border-style: none;
          width: 100%;
          height: 100%;
        }
      }
      .topleft {
        align-items: center;
        justify-content: space-around;
        flex-wrap: wrap;
        margin: 10px 0;
        .row1,
        .row2 {
          display: flex;
          border-bottom: $mborderbottom;
          p {
            display: inline-block;
            width: 150px;
            line-height: 40px;
            span {
              margin-left: 10px;
            }
          }
        }
      }
    }
    .rightr {
      height: 300px;
      .title1box {
        padding: 0 20px;
        .title1row {
          overflow: hidden;
          .title1 {
            color: #000;
            font-weight: bold;
            float: left;
            font-size: 16px;
          }
          .projectId {
            background-color: #ffb800;
            color: #fff;
            font-size: 12px;
            line-height: 20px;
            border-radius: 10px;
            padding: 0 10px;
            float: right;
          }
        }
        .description2 {
          display: flex;
          flex-wrap: wrap;
          line-height: 30px;
          margin: 10px 0;
          .title4 {
            color: $mtcolor4;
            font-size: 14px;
          }
          .title41 {
            display: inline-block;
            width: 50%;
          }
          .title42 {
            display: block;
          }
        }
      }
      .flagstar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 14px;
        .block1 {
          position: relative;
          width: 33.3%;
          text-align: center;
          padding: 20px 0;
          .title3 {
            color: #999;
            font-size: 12px;
          }
          i {
            font-size: 18px;
            color:orangered;
          }
        }
        .block1:nth-child(2)::before {
          content: "";
          display: inline-block;
          height: 100%;
          width: 1px;
          border-left: $mborderbottom;
          position: absolute;
          left: 0;
          top: 0;
        }
        .block1:nth-child(2)::after {
          content: "";
          display: inline-block;
          height: 100%;
          width: 1px;
          border-left: $mborderbottom;
          position: absolute;
          right: 0;
          top: 0;
        }
      }
      .tabcontainer {
        height: 200px;
        /deep/ .el-tabs {
          height: 100%;
        }
        /deep/ .el-tabs__active-bar,
        /deep/ .el-tabs__nav-wrap::after {
          height: 0px;
        }
        /deep/ .el-tabs__item {
          border: 1px solid $mcolor1;
          margin: 0 5px;
          padding: 0 10px;
        }
        /deep/ .el-tabs__item:nth-child(-n + 7) {
          color: $mcolor1;
        }
        /deep/ .is-active {
          background-color: #409eff !important;
          color: #fff !important;
        }
        /deep/ .el-tabs__item:hover {
          background-color: #409eff;
          color: #fff;
        }
        //  以下是card的样式
        /deep/ .el-tabs__content {
          width: 100%;
          height: 80%;
          background: $mbgccolor2;
          padding: 20px;
        }
      }
    }
  }
  // 档案及其他
  .danganqita {
    padding: 0 20px;
    .layui-card-header {
      background: #f0f0f0;
      border: 1px solid #d4d4d4;
      border-bottom: 2px solid #d4d4d4;
    }
    .layui-card-body {
      border: 1px solid #d4d4d4;
    }
    .qita {
      padding-left: 5px;
    }
  }
}
</style>
