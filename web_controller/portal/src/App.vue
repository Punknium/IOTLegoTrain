<template>
  <v-app id="app" class="app pa-4">
    <router-view class="app__view"/>
  </v-app>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
html, body, .application, .application--wrap {
  min-height: 100% !important;
  height: 100% !important;
  max-height: 100% !important;
}
</style>
