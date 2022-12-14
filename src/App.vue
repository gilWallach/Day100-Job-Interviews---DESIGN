<template>
  <div class="main-layout">
    <app-header />
    <main>
      <div class="inner-layout">
        <app-hero />
        <app-features />
      </div>
      <app-stay-productive />
    </main>
  </div>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import appHeader from './components/app-header.vue'
import appHero from './components/app-hero.vue'
import appFeatures from './components/app-features.vue'
import appStayProductive from './components/app-stay-productive.vue'
</script>