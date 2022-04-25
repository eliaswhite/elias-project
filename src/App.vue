<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CAbeçalho from "@/components/CAbeçalho.vue";

export default {
  components: { MenuLateral, CAbeçalho },
};
</script>
<template>
  <MenuLateral />
  <CAbeçalho />
  <main id="content">Principal</main>
  <footer id="footer">Rodapé</footer>
</template>
<style></style>
