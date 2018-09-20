<template>
  <b-container>
    <b-row>
      <headers></headers>
      <b-col></b-col>
    </b-row>
    <b-row>
      <lists></lists>
      <logos></logos>
    </b-row>
    <br/>
  </b-container>
</template>

<script>

import headers from './headers.vue'
import lists from './lists.vue'
import logos from './logos.vue'

export default {
  components:{
    headers,
    lists,
    logos
  }
}
</script>

<style scoped>
</style>
