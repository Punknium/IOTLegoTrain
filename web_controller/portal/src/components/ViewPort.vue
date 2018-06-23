<template>
  <v-card raised class="view-port" light>
    <v-card-media class="view-port__media" src="/static/20180622_191404.jpg" contain></v-card-media>
  </v-card>
</template>

<script>
export default {
  name: 'ViewPort',
}
</script>

<style scoped>
.view-port {
}
.view-port__media {
  height: 0;
  padding-top: 56.25%;
}
</style>
