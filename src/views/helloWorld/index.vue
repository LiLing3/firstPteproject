<template>
  <div>
    <h1>hello {{name}}!</h1>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      name: "world"
    };
  }
};
</script>
 
<style lang="less" scoped>
h1 {
  color: red;
}
</style>