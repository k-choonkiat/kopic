<template>
  <span>
    <HelloWorld></HelloWorld>
  </span>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld';
export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
