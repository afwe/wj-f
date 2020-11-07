<template>
  <el-container>
    <el-aside style="width: 200px;margin-top: 20px">
      <switch></switch>
      <SideMenu></SideMenu>
    </el-aside>
    <el-main>
      <book></book>
    </el-main>
  </el-container>
</template>

<script>
  import SideMenu from './SideMenu'
  const book=()=> import('./Books')
  export default {
    name: 'AppLibrary',
    components:{SideMenu,book}
  }
</script>
<style scoped>
</style>

