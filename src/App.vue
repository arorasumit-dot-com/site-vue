<template>
  <div id="app">
    <NavBar></NavBar>
    <router-view></router-view>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';
import VueRouter, { RouteConfig } from 'vue-router';

import Home from './pages/Home.vue';
import Education from './pages/Education.vue';
import Experience from './pages/Experience.vue';
import Spoken from './pages/Spoken.vue';

import NavBar from './components/NavBar.vue';

const PageNotFound = { template: '<div>404</div>' };

const routes: RouteConfig[] = [
  { path: '/', component: Home },
  { path: '/education', component: Education },
  { path: '/experience', component: Experience },
  { path: '/spoken', component: Spoken },
  { path: '**', component: PageNotFound },
];

const router = new VueRouter({ routes });
Vue.use(VueRouter);

@Component({ components: { NavBar }, router: router })
export default class App extends Vue {
  mixins = [VueRouter];

  constructor() {
    super(router);
  }
}
</script>

<style lang="scss">

</style>
