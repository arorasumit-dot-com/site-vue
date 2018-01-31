<template>
  <a class="nav-bar-link" :href="url">
    {{title}}
  </a>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component, Prop } from 'vue-property-decorator';

@Component({})
export default class NavBarLink extends Vue {
  @Prop() title: String;
  @Prop() url: String;
}
</script>

<style lang="scss" scoped>
.nav-bar-link {
  flex-grow: 1;
  text-align: center;
  height: 60px;
  line-height: 60px;
}
a {
  color: #fff;
  text-decoration: none;
}
</style>
