<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
	<div class="f f-jc-sb f-ai-c page-header">
    <div>{{ msg }}</div>
		<img class="avatar" alt="Vue logo" src="@/assets/logo.png" />
	</div>
</template>

<style src="./styles/index.css" scoped></style>
