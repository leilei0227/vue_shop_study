<template>
  <div class="container">
    <el-button type="info" @click="logout">退出</el-button>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {}
  },
  props: {},
  components: {},
  watch: {},
  computed: {},
  methods: {
    logout() {
      window.sessionStorage.clear()
      this.$router.push('/login')
    }
  },
  created() {},
  mounted() {}
}
</script>

<style scoped lang="less">
</style>
