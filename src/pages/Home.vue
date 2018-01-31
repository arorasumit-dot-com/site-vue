<template>
<div class="ma0 pa0 home h-100 flex flex-column justify-center white w-100 vh-100">
  <p class="f-headline-ns f1 tc ma4">Hi, I am Sumit Arora</p>
  <p class="f-subheadline-ns f2 tc ma4">a full stack developer at rangle.io</p>
  <div class="tc ma4">
    <a href="https://twitter.com/arorasumit" target="_blank">
      <i class="fa fa-twitter fa-3x white"></i>
    </a>
    &nbsp;&nbsp;
    <a href="https://github.com/sumitarora" target="_blank">
      <i class="fa fa-github fa-3x white"></i>
    </a>
    &nbsp;&nbsp;
    <a href="https://linkedin.com/in/arorasumit85" target="_blank">
      <i class="fa fa-linkedin fa-3x white"></i>
    </a>
    &nbsp;&nbsp;
    <a href="mailto:er.sumitarora@gmail.com" target="_blank">
      <i class="fa fa-envelope-o fa-3x white"></i>
    </a>
  </div>
</div>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component, Prop } from 'vue-property-decorator';

@Component({})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
.home {
  background-color: #fe4365;
}
</style>
