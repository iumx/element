<template>
  <div style="margin: 20px;">
          <el-time-picker style="margin-left: 20px;"
    v-model="value1"
    format="HH:mm:ss"
    placeholder="任意时间点">
  </el-time-picker>

  <el-time-picker style="margin-left: 20px;"
    v-model="value1"
    format="时间：HH时mm分ss秒"
    placeholder="任意时间点">
  </el-time-picker>

    <el-time-picker style="margin-left: 20px;"
    v-model="value1"
    format="前缀 HH:mm:ss 后缀"
    placeholder="任意时间点">
  </el-time-picker>



  </div>
</template>

<script>
  export default {
    data() {
      return {
         value1: new Date()
      };
    }
  };
</script>
