<script lang="js" setup>
const { blockId }= defineProps(['blockId']);

const array = window.yaContextCb || [];
array.push(() => {
  Ya.Context.AdvManager.render({
    blockId: blockId,
    renderTo: `yandex_rtb_${blockId}`,
  });
});

</script>
<template>
  <div style="padding-top: 10px; padding-bottom: 10px; max-height: 200px">
    <div :id="'yandex_rtb_' + blockId"></div>
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
