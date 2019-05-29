<template>
  <div class="page">
    <div class="box"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box {
  margin: 10px;
  border: 1px solid #e2e2e2;
  height: 40px;
}

.box:hover {
  border: 1px solid #aaeeff;
}
</style>
