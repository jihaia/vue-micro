<template>
  <v-app light>
    <app-bar />
    <main>
        <v-container fluid>
          <router-view></router-view>
        </v-container>
    </main>
  </v-app>
</template>

<script>
import AppBar from './components/core/AppBar'
export default {
  name: 'app',
  components: {
    AppBar
  }
}
</script>

<style lang="stylus">
  @import './stylus/main'
</style>
