<template></template>
<script setup lang="ts">
import { onMounted } from "vue";
import TypeIt from "typeit";

onMounted(() => {
  new TypeIt(".tagline", {
    strings: [
      "处理和分析海量、多样、高速增长的数据集，以提取有价值的信息，常用于决策支持和预测分析。",
    ],
    speed: 200,
  }).go();
});
</script>
