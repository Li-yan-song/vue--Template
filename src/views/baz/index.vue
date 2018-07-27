<template>
  <div class="baz">
    <el-input v-model="state" placeholder="请输入角色名" class="baz-input"></el-input>
    <ul>
      <li v-for="item in items" :key="item.id" class="baz-item">{{item.name}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      state: '',
      items: [
        { name: '默认管理员', id: 1 },
        { name: '代理商角色', id: 2 },
        { name: '业务员角色', id: 3 },
        { name: '分公司经理', id: 4 },
        { name: '分公司财务', id: 5 },
        { name: '大区经理', id: 6 },
        { name: '大区财务', id: 7 },
        { name: '事业部经理', id: 8 },
        { name: '事业部财务', id: 9 },
        { name: '事业部分货', id: 10 },
        { name: '事业部上午', id: 11 },
        { name: '文档管理员', id: 12 },
        { name: '物流员角色', id: 13 }
      ]
    }
  }
}
</script>


<style>
  .baz-input{
    width: 200px !important;
    margin-left: 10px;
  }
  .baz-item{
    list-style-type: none;
    height: 30px;
    line-height: 30px;
    margin-left: -30px;
  }
</style>
