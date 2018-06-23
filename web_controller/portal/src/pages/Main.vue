<template>
  <v-container>
    <v-layout class="layout" row>
      <v-flex xs12 sm8 offset-sm2>
        <view-port/>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import ViewPort from '@/components/ViewPort'

export default {
  name: 'Main',
  components: {
    ViewPort,
  },
}
</script>

<style scoped>
</style>
