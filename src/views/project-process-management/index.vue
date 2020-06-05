<template>
  <div class="project-process-management">
    <div class="word">{{ msg }}</div><!-- <el-tabs v-model="activeName" @tab-click="handleClick">
      <el-tab-pane label="项目概况" name="gaikuang">新建全新、独立的数字化信贷系统，将其打造成为数字化信贷平台的核心。重新设计业务管理模块，实现圈子内的业务处理模式。</el-tab-pane>
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
    </el-tabs> -->
    <div class="buttab">
      <ul class="labels">
        <li class="labeltag">项目概况</li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
        <li class="labeltag"></li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: 'project-process-management',
  data() {
    return {
      activeName: 'gaikuang'
    }
  },
  methods: {
    handleClick(tab, event) {
      console.log(tab, event)
    }
  },
  computed: {
    // layui.use('element', function(){
    //   var element = layui.element;
    // })
  }
}
</script>
<style lang="scss" scoped>
.word {
  color: violet;
}
</style>
