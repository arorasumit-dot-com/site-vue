<template>
<div class="ma0 pa4 home h-100 flex flex-column education white  w-100 vh-100">
  <div class="w-60-ns w-80-m w-100 center">
    <div class="flex pa4-ns pa1">
      <img src="/assets/centennial-logo.jpg" class="br-100 h4-ns h3 w4-ns w3 dib ba b--black-05 pa2-ns pa1" />
      <div class="pl4">
        <p class="f2-ns f3 mt2 mb2">Centennial College</p>
        <p class="f3-ns f4">Software Engineering Technology (Fast Track), Computer Software Engineering</p>
        <p class="f4-ns f5">2012 – 2014</p>
      </div>
    </div>
    <div class="flex pa4-ns pa1">
      <img src="/assets/ptu-logo.png" class="br-100 h4-ns w4-ns h3 w3 dib ba b--black-05 pa2-ns pa1" />
      <div class="pl4">
        <p class="f2-ns f3 mt2 mb2">Punjab Technical University</p>
        <p class="f3-ns f4">B Tech., Computer Science</p>
        <p class="f4-ns f5">2004 – 2008</p>
      </div>
    </div>
  </div>
</div>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component, Prop } from 'vue-property-decorator';

@Component({})
export default class Education extends Vue {}
</script>

<style lang="scss" scoped>
.education {
  background-color: #4ecdc4;
}
</style>
