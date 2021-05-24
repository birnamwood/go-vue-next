<template>
  <div class="header">
    <span class="header-title">title</span>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

export default class Header extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  height: 50px;
  background-color: green;
  display: flex;
}
.header-title {
  font-size: 24px;
}
</style>