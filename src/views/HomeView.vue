<!--
 * @Author: liuyanxin
 * @Date: 2024-01-02 13:54:59
 * @LastEditTime: 2024-01-02 13:55:01
 * @LastEditors: liuyanxin
 * @Description: 
 * @FilePath: /vue2-cli/src/views/HomeView.vue
-->
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
