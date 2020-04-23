<template>
  <div class="wrap">
   {{msg}}
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  data() {
	  return {
		  msg:"这里是登录页"
	  }
  },
}
</script>
<style lang="scss" scoped>
	.wrap{
		height: 100vh;
		background: green;
	}
</style>
