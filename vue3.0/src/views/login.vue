<template>
  <div class="wrap">
	<button @click="sldkfjls">获取数据按钮</button>
	<hello-world ref="slkdfj" > </hello-world>
  </div>
</template>

<script>
import HelloWorld from "../components/HelloWorld"
export default {
  name: "Home",
  components: {
	  HelloWorld
  },
  data() {
    return {
      msg: "这里是登录页"
    };
  },
  methods: {
	  sldkfjls(){
		  console.log(this.$refs.slkdfj);
		  console.log(this.$refs.slkdfj.sdfklasd);
	  }
  },
};
</script>
<style lang="scss" scoped>
.wrap {
  height: 100vh;
  background: green;
}
</style>
