<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <CustomComp newHere="This is second message" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import CustomComp from '@/components/CustomComp.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    CustomComp
  }
};
</script>
