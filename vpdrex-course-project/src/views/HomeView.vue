<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/drexel_logo.png">
    <HomePage msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HomePage from '@/components/HomePage.vue' // @ is an alias to /src

@Options({
  components: {
    HomePage
  }
})
export default class HomeView extends Vue {}
</script>
