<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title>uptune</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>
