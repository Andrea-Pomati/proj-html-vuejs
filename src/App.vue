<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import ExcellenceInServices from './components/ExcellenceInServices.vue';
import LatestNews from './components/LatestNews.vue';
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
    TeamOfExperts,
    LatestNews
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
<LatestNews></LatestNews>

</template>

<style lang="scss" scoped>

</style>
