<template>
  <div id="main">
    <Header/>
    <router-view />
  </div>
</template>

<script lang="ts">
import Header from "@/components/Header.vue"; // @ is an alias to /src
import { Options, Vue } from "vue-class-component";
@Options({
  components: {
    Header
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}
</style>