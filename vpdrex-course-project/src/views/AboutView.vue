<template>
  <AboutPage></AboutPage>
</template>

<script type="ts">

import { Vue, Options } from 'vue-class-component'
import AboutPage from '@/components/AboutPage.vue'

@Options({
  components: {
    AboutPage
  }
})

export default class HomeView extends Vue {}
</script>
