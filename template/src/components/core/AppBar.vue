<template>
  <v-toolbar fixed dense dark>
    <v-toolbar-side-icon ></v-toolbar-side-icon>
    <v-toolbar-title>{{ name }}</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn icon>
      <v-icon>fa-bell</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>history</v-icon>
    </v-btn>
    <v-btn class="blue-grey darken-3">
      Jason Ihaia
    </v-btn>
    <v-btn icon>
      <v-icon>apps</v-icon>
    </v-btn>
  </v-toolbar>
</template>

<script>
  export default {
    name: 'app-bar'
  }
</script>
