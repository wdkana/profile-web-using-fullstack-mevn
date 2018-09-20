<!--                        -->
<!-- autoload navbar in App.js  -->
<!--                        -->

<template>
  <b-container fluid>
    <b-row>
      <infoProfile></infoProfile>
      <skillSet></skillSet>
    </b-row>
    <br/>
    <softSkill></softSkill>
    <jumbotron></jumbotron>
  </b-container>
</template>

<script>

import infoProfile from './infoProfile.vue'
import skillSet from './skillSet.vue'
import jumbotron from './jumbotron.vue'
import softSkill from './softSkill.vue'

export default {
  components:{
    infoProfile,
    skillSet,
    jumbotron,
    softSkill
  }
}
</script>

<style scoped>
</style>
