<template>
  <v-toolbar fixed dense dark class="blue-grey">
    <v-toolbar-side-icon @click.native.stop="toggleNavigator"></v-toolbar-side-icon>
    <v-toolbar-title>Sample</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn icon>
      <v-icon>fa fa-bell</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>history</v-icon>
    </v-btn>
    <v-btn class="pink white--text">
      Full Name
    </v-btn>
    <v-btn icon @click.native.stop="toggleChooser">
      <v-icon>apps</v-icon>
    </v-btn>
  </v-toolbar>
</template>

<script>
  import { mapActions } from 'vuex'

  export default {
    name: 'app-bar',
    methods: {
      ...mapActions([
        'toggleNavigator',
        'toggleChooser'
      ])
    }
  }
</script>
