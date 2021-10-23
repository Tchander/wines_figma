<template>
  <div>
    <header-section />
    <best-taste />
    <collection />
  </div>
</template>

<script>
import HeaderSection from "../components/HeaderSection";
import BestTaste from "../components/BestTaste";
import Collection from "../components/Collection";
export default {
  name: "Home",
  components: { Collection, BestTaste, HeaderSection },
};
</script>
