<script>
export default {
  data() {
    return {
      times: [
        {
          time: "Atlético Mineiro",
          flag: new URL("./img/atleticomg.png", import.meta.url).href,
        },
        {
          time: "Avai",
          flag: new URL("./img/avai-fc-logo-escudo-1.png", import.meta.url)
            .href,
        },
        {
          time: "América Mineiro",
          flag: new URL("./img/amer.png", import.meta.url).href,
        },
        {
          time: "Atlético Goianiense",
          flag: new URL("./img/at.png", import.meta.url).href,
        },
        {
          time: "Atlético paranaense",
          flag: new URL("./img/cap.png", import.meta.url).href,
        },
        { time: "Ceara", flag: new URL("./img/cea.png", import.meta.url).href },
        {
          time: "Corinthians",
          flag: new URL("./img/cor.png", import.meta.url).href,
        },
        {
          time: "Flamengo",
          flag: new URL("./img/fla.png", import.meta.url).href,
        },
        {
          time: "Fluminense",
          flag: new URL("./img/flu.png", import.meta.url).href,
        },
        {
          time: "Fortaleza",
          flag: new URL("./img/for.png", import.meta.url).href,
        },
        { time: "Goiás", flag: new URL("./img/go.png", import.meta.url).href },
        {
          time: "Cuiabá",
          flag: new URL("./img/i 1.png", import.meta.url).href,
        },
        {
          time: "Internacional",
          flag: new URL("./img/inter.png", import.meta.url).href,
        },
        {
          time: "Juventude",
          flag: new URL("./img/juv.png", import.meta.url).href,
        },
        {
          time: "Palmeiras",
          flag: new URL("./img/pal.png", import.meta.url).href,
        },
        {
          time: "Red Bull Bragantino",
          flag: new URL("./img/red.png", import.meta.url).href,
        },
        {
          time: "Santos",
          flag: new URL("./img/san.png", import.meta.url).href,
        },
        {
          time: "São Paulo",
          flag: new URL("./img/sao.png", import.meta.url).href,
        },
      ],
    };
  },
};
</script>
<template>
  <aside id="sidenav">
    <img
      v-for="(time, i) of times"
      :key="i"
      :src="time.flag"
      :title="time.time"
    />
  </aside>
</template>
<style></style>
