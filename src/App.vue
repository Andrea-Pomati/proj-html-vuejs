<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import ExcellenceInServices from './components/ExcellenceInServices.vue';
import KnowFirst from './components/KnowFirst.vue';
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
    LatestNews,
    KnowFirst,
    AppFooter
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
<KnowFirst></KnowFirst>
<AppFooter></AppFooter>
</template>

<style lang="scss" scoped>

</style>
