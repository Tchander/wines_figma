<template>
  <div>
    <header-section />
    <best-taste />
    <collection />
    <degustation />
    <footer-section />
  </div>
</template>

<script>
import HeaderSection from "../components/HeaderSection";
import BestTaste from "../components/BestTaste";
import Collection from "../components/Collection";
import Degustation from "../components/Degustation";
import FooterSection from "../components/FooterSection";
export default {
  name: "Home",
  components: {
    FooterSection,
    Degustation,
    Collection,
    BestTaste,
    HeaderSection,
  },
};
</script>
