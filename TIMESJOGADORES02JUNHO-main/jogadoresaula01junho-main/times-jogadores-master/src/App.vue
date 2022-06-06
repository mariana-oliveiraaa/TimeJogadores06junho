<script setup>
 import HeaderComp from "@/components/template/HeaderComp.vue";
 import RodapeComp from "@/components/template/RodapeComp.vue";
</script>

<template>
 <HeaderComp />
 <RouterView />
 <RodapeComp />
</template>

<style>
@import "@/assets/base.css";
#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

header,
footer {
  background-color: rgb(1, 143, 148);
  color: rgb(255, 255, 255);
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}

main {
  height: 70%;
}

</style>