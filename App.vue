<template>
<div class="app">Hi</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
	name: 'App',
	computed: {
		showProgressPanel(): boolean {
			return true;
		},
	},
});
</script>
