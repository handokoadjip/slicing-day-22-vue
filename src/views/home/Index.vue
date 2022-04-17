<template>
  <TitleComponent />
  <JumbotronComponent />
  <AboutClientComponent />
  <ComodityTradingComponent />
  <ReportComponent />
</template>

<script>
import TitleComponent from "@/components/TitleComponent.vue";
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import AboutClientComponent from "@/components/AboutClientComponent.vue";
import ComodityTradingComponent from "@/components/ComodityTradingComponent.vue";
import ReportComponent from "@/components/ReportComponent.vue";

export default {
  name: "HomePage",
  components: {
    TitleComponent,
    JumbotronComponent,
    AboutClientComponent,
    ComodityTradingComponent,
    ReportComponent,
  },
  mounted() {
    document.title = "Eleks Website | IXM"
  }
}
</script>
