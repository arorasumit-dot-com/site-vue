<template>
  <div class="nav-bar">
    <NavBarLink class="home" title="Home" url="/#/"></NavBarLink>
    <NavBarLink class="education" title="Education" url="/#/education"></NavBarLink>
    <NavBarLink class="experience" title="Experience" url="/#/experience"></NavBarLink>
    <NavBarLink class="spoken" title="Spoken" url="/#/spoken"></NavBarLink>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

import NavBarLink from './NavBarLink.vue';

@Component({
  components: { NavBarLink },
})
export default class NavBar extends Vue {}
</script>

<style lang="scss" scoped>
.nav-bar {
  width: 100%;
  display: flex;
  flex-direction: row;
}

.home {
  background-color: #fe4365;
}

.about {
  background-color: #c8c8a9;
}

.skills {
  background-color: #ff6b6b;
}

.education {
  background-color: #4ecdc4;
}

.experience {
  background-color: rebeccapurple;
}

.spoken {
  background-color: #cc333f;
}

.blog {
  background-color: #6a4a3c;
}

.contact {
  background-color: #7a6a53;
}
</style>
