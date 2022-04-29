<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
import BlocoCabecalho from "./components/BlocoCabecalho.vue";

export default {
  components: { MenuLateral, BlocoPrincipal, BlocoCabecalho },
};
</script>
<template>
  <MenuLateral />
  <BlocoCabecalho />
  <BlocoPrincipal />
</template>
<style></style>
