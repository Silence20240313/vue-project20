<template>
  <div>
    <el-row>
        <!-- 按钮 -->
      <el-button>{{primaryButton1}}</el-button>
      <el-button type="primary" v-on:click = "print()">{{primaryButton2}}</el-button>
      <el-button type="success">{{primaryButton3}}</el-button>
      <el-button type="info">{{primaryButton4}}</el-button>
      <el-button type="warning">{{primaryButton5}}</el-button>
      <el-button type="danger">{{primaryButton6}}</el-button>
    </el-row>

    
  </div>
</template>

<script>
export default {
    name: 'Demo-1',
    data() {
        return {
            primaryButton1: "默认按钮",
            primaryButton2: "主要按钮",
            primaryButton3: "成功按钮",
            primaryButton4: "信息按钮",
            primaryButton5: "警告按钮",
            primaryButton6: "危险按钮"
        }
    },
    methods:{
        print:function(){
            alert('Hello');
        }
    }
};
</script>

<style >
</style>