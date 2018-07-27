<template>
  <div class="bar">
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
          label: '鸿合科技',
          children: [
            { label: '鸿合科技-信息部' },
            { label: '鸿合科技-财务部' },
            { label: '鸿合科技-营销中心' },
            { label: '鸿合科技-营销中心' },
            { label: '鸿合科技-营销中心' },
            { label: '东北大区' },
            { label: '西北大区' },
            { label: '西南大区' },
            { label: '鲁豫大区' },
            { label: '华北大区' },
            { label: '华中大区' },
            { label: '浙沪赣大区' },
            { label: '华南大区' }
          ]
        }
      ]
    }
  }
}
</script>

