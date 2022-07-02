<template>
    <div class="container">
        <div class="form-container">
        </div>
      <el-form
    label-width="100px"
    style="max-width: 460px"
    class="loginForm"
  >
    <el-form-item label="邮箱" prop="email">
      <el-input placeholder="Enter email" />
    </el-form-item>
    <el-form-item label="密码" prop="pass">
      <el-input placeholder="Enter Pass" />
    </el-form-item>
    <el-form-item>
      <el-button type="primary">提交</el-button>
    </el-form-item>
  </el-form>

  <div class="tiparea">
      <p>忘记密码?<a>立即找回</a></p>
  </div>
    </div>
</template>

<script>
export default {
    name:'Login',
    component:{

    }
}
</script>

<style scoped>

</style>