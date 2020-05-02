<template>
  <div class="home">
    <HeaderDavalyze />
    <HeroDavalyze />
    <WomenDavalyze />
    <InstaDavalyze />
    <PartnerDavalyze />
    <FooterDavalyze />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

import HeaderDavalyze from "@/components/HeaderDavalyze";
import HeroDavalyze from "@/components/HeroDavalyze";
import WomenDavalyze from "@/components/WomenDavalyze";
import InstaDavalyze from "@/components/InstaDavalyze";
import PartnerDavalyze from "@/components/PartnerDavalyze";
import FooterDavalyze from "@/components/FooterDavalyze";

export default {
  name: "Home",
  components: {
    // HelloWorld
    HeaderDavalyze,
    HeroDavalyze,
    WomenDavalyze,
    InstaDavalyze,
    PartnerDavalyze,
    FooterDavalyze
  }
};
</script>
