<script lang="js" setup>
import {  defineComponent } from 'vue'
window.yaContextCb.push(() => {
  const { blockId }= defineProps(['blockId']);
  Ya.Context.AdvManager.render({
    blockId: blockId,
    renderTo: `yandex_rtb_${blockId}`,
  });
});
</script>
<template>
  <div style="padding-top: 10px; padding-bottom: 10px; max-height: 200px">
    <div :id="`yandex_rtb_${blockId}`"></div>
  </div>
</template>

<script lang="js">
import { defineComponent } from "vue";

export default defineComponent({
  name: "YandexAD",
  props: {
		blockId: String,
	},
});
</script>
