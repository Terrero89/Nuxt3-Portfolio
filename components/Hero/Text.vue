
<script setup lang="ts">
import type { Ref } from 'vue'


const year: Ref<string | number> = ref(2020);
const name: Ref<string> = ref("Sergio");
const age : Ref<number > = ref(25)
</script>

<template>
  <div>{{ name }}</div>
  <div>{{( year )}}</div>
  <div>{{( age +5)}}</div>
</template>
