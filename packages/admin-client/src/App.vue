<script setup lang="ts">
import Navbar from './components/navbar/index.vue'
import PageHeader from './components/page-header/index.vue'
</script>

<template>
	<Navbar />
  <div class="f-f-1 f f-fd-c">
    <PageHeader msg="顶部" />
    <div class="main">内容区</div>
  </div>
</template>

<style src="./styles/index.css"></style>
