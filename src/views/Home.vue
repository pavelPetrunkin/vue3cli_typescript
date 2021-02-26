<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Lists msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Lists from "@/components/Lists.vue"; // @ is an alias to /src

@Options({
  components: {
    Lists
  }
})
export default class Home extends Vue {}
</script>
