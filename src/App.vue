<template>
  <div id="App">
    <Home/>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue';
  import {Component} from 'vue-property-decorator';
  import Home from '@/views/Home.vue';

  @Component({
    components: {Home}
  })
  export default class App extends Vue {

  }
</script>

<style>
  @import "~@/assets/style/reset.scss";
  @import "~@/assets/style/helper.scss";
</style>
