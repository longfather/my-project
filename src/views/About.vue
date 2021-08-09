<template>
  <div class="about">
    <HelloWorld1 msg="HelloWorld!" />
    <a href="www.biadu.com">baidu</a>
  </div>
</template>
<script>
import HelloWorld1 from '@/components/HelloWorld.vue';
export default {
  name: "About",
  components: {
    HelloWorld1,
  },
};
</script>
