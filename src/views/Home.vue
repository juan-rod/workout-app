<template>
  <div class="home border1">
    <WorkoutPrograms/>
    <div class="wo-data border2"></div>
    <footer class="footer border2"></footer>
  </div>
</template>

<script>
// @ is an alias to /src
import WorkoutPrograms from '@/components/WorkoutPrograms.vue'
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'home',
  components: {
    NavBar,
    WorkoutPrograms
  }
}
</script>
