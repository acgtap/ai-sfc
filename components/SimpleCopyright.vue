<script lang="ts" setup>
import pkg from '~/package.json'
</script>

<template>
  <div text="center sm" my-3>
    <CurrentVersion />
    <div flex="~" items-center justify-center gap="2">
      <a
        :href="" target="_blank"
        class="inline-flex items-center justify-center"
      >
        <div i-ri-github-line mr-1 />
        <span>Code</span>
      </a>
      by
      <a
        href="https://qm.qq.com/q/jhzFDyBPz4" target="_blank"
        class="inline-flex items-center justify-center"
      >
        <div i-ri-bilibili-line mr-1 class="text-pink-400" />
        <span>惠惠</span>
      </a>
    </div>
  </div>
</template>
