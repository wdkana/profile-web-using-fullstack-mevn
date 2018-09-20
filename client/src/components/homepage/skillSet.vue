<template>
<!-- column size = 4 -->
    <b-col cols="12" md="4">
        <b-card text-variant="black" title="Skill Set" style="height:100%;text-align:center;box-shadow: 2px 3px 3px 2px #f2f2f2">
          <p class="card-text">
            <b-list-group>
              <b-list-group-item class="d-flex justify-content-between align-items-center">
                <p v-for="skill in skills" :key=skill.item1 >{{skill.item1}}</p>
                <b-badge variant="dark" pill v-for="value in skills_value" :key=value.item1>{{value.item1}}</b-badge>
              </b-list-group-item>
              <b-list-group-item class="d-flex justify-content-between align-items-center">
                <p v-for="skill in skills" :key=skill.item2 >{{skill.item2}}</p>
                <b-badge variant="dark" pill v-for="value in skills_value" :key=value.item2 > {{value.item2}} </b-badge>
              </b-list-group-item>
              <b-list-group-item class="d-flex justify-content-between align-items-center">
                <p v-for="skill in skills" :key=skill.item3 >{{skill.item3}}</p>
                <b-badge variant="dark" pill v-for="value in skills_value" :key=value.item3 > {{value.item3}}</b-badge>
              </b-list-group-item>
            </b-list-group>
          </p>
          <b-button @click="showModal" variant="dark" style="width:120px">Hire Me</b-button>
        </b-card>
        
        <!-- hire me modal -->
        <b-modal ref="myModalRef" hide-footer title="Thanks for interested with me">
          <div class="d-block text-center">
            <b-form inline>
              <b-input class="mt-4 mb-12" id="margintop" placeholder="your business contact" />
            </b-form>
          </div>
          <b-btn class="mt-3" variant="outline-danger" block @click="hideModal">Close Me</b-btn>
        </b-modal>
      </b-col>
      <!-- end of hire me modal -->
      
</template>

<script>
export default {
  data () {
    return {
      skills: [{
        item1: "JAVASCRIPT",
        item2: "PHP",
        item3: "HTML CSS"
      }],
      skills_value: [{
        item1: 85,
        item2: 90,
        item3: 95
      }]
    }
  },
   methods: {
    showModal () {
      this.$refs.myModalRef.show()
    },
    hideModal () {
      this.$refs.myModalRef.hide()
    }
  }
}
</script>

<style scoped>
  p {
    font-size: 24px;
  }
</style>
