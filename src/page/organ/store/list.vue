
<template>
  <div>
    <span>我是仓库资料列表</span>
    <div>
      <button @click = "jump ('/organ/store/info/666')" >列表详情</button>
    </div>
  </div>
</template>
<script>
export default {
  methods: {
    jump (data) {
      this.$router.push({
        path: data
      })
    }
  }
}
</script>
