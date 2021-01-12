<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Clock />
  </div>
</template>

<script>
// @ is an alias to /src
import Clock from '@/components/clock.vue'

export default {
  name: 'Home',
  components: {
    Clock
  }
}
</script>
