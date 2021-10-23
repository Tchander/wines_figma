<template>
  <div>
    <header-section />
    <best-taste />
    <collection />
    <degustation />
  </div>
</template>

<script>
import HeaderSection from "../components/HeaderSection";
import BestTaste from "../components/BestTaste";
import Collection from "../components/Collection";
import Degustation from "../components/Degustation";
export default {
  name: "Home",
  components: { Degustation, Collection, BestTaste, HeaderSection },
};
</script>
