<template>
  <div class="foo">
    <el-tree :data="data" :default-expand-all="true">

    </el-tree>

  </div>
</template>

<script>
  
  export default {
    data() {
      return {
        data: [
          {
            label: '首页',
            children: [
              { label: '我的待办' },
              { label: '我的关注' },
              { label: '我的公告' }
            ]
          },
          {
            label: '基础数据',
            children: [
              { label: '客户' },
              { label: '产品' }
            ]
          },
          {
            label: '业务申请',
            children: [
              { label: '项目报备单' },
              { label: '合同申请单' },
              { label: '交货申请单' },
              { label: '转储申请单' },
              { label: '合同执行' },
              { lable: '测试申请单' }
            ]
          }
        ]
      }
    }
  }
</script>
