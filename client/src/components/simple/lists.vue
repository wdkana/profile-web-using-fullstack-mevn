<template>
<b-col cols="12" md="8" fluid class="mb-2">
    <b-list-group style="margin-top: 20px">
        <education></education>
        <experience></experience>
        <skill></skill>
    </b-list-group>
</b-col>
</template>

<script>
import education from './list/education.vue'
import experience from './list/experience.vue'
import skill from './list/skill.vue'
export default {
    components: {
        education,
        experience,
        skill
    }
}
</script>

<style scoped>
    .linking:hover{
        text-decoration: none;
        transition: .3s;
        background: #ffffff;
        font-size:18px
    }
</style>
