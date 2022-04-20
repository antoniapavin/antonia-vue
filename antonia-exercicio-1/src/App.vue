<script>
import MenuLateral from "@/components/MenuLateral.vue";
import MainPrincipal from "@/components/MainPrincipal.vue";
import HeaderCabecalho from "./components/HeaderCabecalho.vue";
import FooterRodape from "./components/FooterRodape.vue";

export default {
  components: { MenuLateral, MainPrincipal, HeaderCabecalho, FooterRodape },
};
</script>

<template>
  <MenuLateral />
  <MainPrincipal />
  <HeaderCabecalho />
  <FooterRodape />
</template>
<style></style>
