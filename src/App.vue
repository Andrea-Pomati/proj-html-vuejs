<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import ExcellenceInServices from './components/ExcellenceInServices.vue';
import ProcessManagement from './components/ProcessManagement.vue';
import TeamOfExperts from './components/TeamOfExperts.vue';
import TheCompany from "./components/TheCompany.vue";
export default {
data() {
    return {
      
    }
  },
  components: {
    AppHeader,
    AppJumbotron,
    TheCompany,
    ExcellenceInServices,
    ProcessManagement,
    TeamOfExperts
}
}

</script>

<template>

<AppHeader></AppHeader>
<AppJumbotron></AppJumbotron>
<TheCompany></TheCompany>
<ExcellenceInServices></ExcellenceInServices>
<ProcessManagement></ProcessManagement>
<TeamOfExperts></TeamOfExperts>

</template>

<style lang="scss" scoped>

</style>
