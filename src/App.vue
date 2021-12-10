<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div h-full text-center flex select-none all:transition-400>
    <div ma>
      <div text-5xl fw100 animate-bounce-alt animate-count-infinite animate-1s>
        unocss
      </div>
      <div op80 text-lg fw300 m1>
        The instant on-demand Atomic CSS engine.
      </div>
      <div class="box">
        อะไรนะ
      </div>
      <div
        m2
        flex
        justify-center
        text-2xl
        op30
        hover="op80"
      >
        <a title="github" rel="noreferrer" i-carbon-logo-github text-inherit href="https://github.com/antfu/unocss" target="_blank">i-carbon-logo-github</a>
      </div>
    </div>
  </div>
  <div class="flex flex-col items-center">
    <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + UnoCSS" />
  </div>
  <div
    absolute
    bottom-5
    right-0
    left-0
    text-center
    op80
  >
    on-demand · instant · fully customizable
  </div>
</template>
