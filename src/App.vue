<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import ExcellenceInServices from './components/ExcellenceInServices.vue';
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
    ExcellenceInServices
}
}

</script>

<template>

<AppHeader></AppHeader>
<AppJumbotron></AppJumbotron>
<TheCompany></TheCompany>
<ExcellenceInServices></ExcellenceInServices>

</template>

<style lang="scss" scoped>

</style>
