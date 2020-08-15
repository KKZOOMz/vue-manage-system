<template>
  <el-container style="height: 100%">
    <el-aside width="200px">
      <CommonAside />
    </el-aside>
    <el-container>
      <el-header>
        <CommonHeader />
      </el-header>
      <el-main>Main</el-main>
    </el-container>
  </el-container>
</template>

<script>
import CommonHeader from '@/components/CommonHeader'
import CommonAside from '@/components/CommonAside'
export default {
  components: {
    CommonHeader,
    CommonAside
  },
  data() {
    return {}
  },
  methods: {}
}
</script>
<style lang="scss"></style>
