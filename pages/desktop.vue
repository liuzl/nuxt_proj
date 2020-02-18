<template>
  <div class="container">
    <a href="#" class="link1">link1</a>
    <a href="#" class="link2">link2</a>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
//alert("Hello World");
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.container a {
  display: block;
  width: 100px;
  height: 100px;
  border: solid 1px #ccc;
  margin: 0 20px;
  line-height: 100px;
}
</style>
