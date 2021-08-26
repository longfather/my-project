<template>
  <div class="about">
    <h3>这里引入了Hello组件</h3>
    <HelloWorld msg="HelloWorld!" />
    <a href="www.biadu.com">baidu</a>
  </div>
</template>
<script>
import HelloWorld from '@/components/HelloWorld.vue';
export default {
  name: "About",
  components: {
    HelloWorld,
  },
};
</script>
