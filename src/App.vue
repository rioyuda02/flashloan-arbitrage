
<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div id='profiles'>
    <img class='i-profile' alt="Vue logo" src="@/assets/i-profile.png"/>

    <div class="wrapper">
      <HelloWorld msg="Hello, I am Rio Yudayanto" />

      <nav >
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About Me</RouterLink>
      </nav>
    </div>
    </div>
  </header>

  <RouterView />
</template>

