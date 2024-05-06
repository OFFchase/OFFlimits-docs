<script lang="js" setup>
window.yaContextCb.push(() => {
  Ya.Context.AdvManager.render({
    blockId: "R-A-8300744-1",
    renderTo: "yandex_rtb_R-A-8300744-1",
  });
});
</script>
<template>
  <head>
    <script>
      window.yaContextCb = window.yaContextCb || [];
    </script>
    <script src="https://yandex.ru/ads/system/context.js" async></script>
  </head>
  <div style="padding-top: 10px; padding-bottom: 10px">
    <div id="yandex_rtb_R-A-8300744-1"></div>
  </div>
</template>

<script lang="js">
import { PropType, defineComponent } from "vue";

export default defineComponent({
  name: "YandexAD",
});
</script>
