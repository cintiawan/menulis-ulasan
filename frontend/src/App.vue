<template>
	<div>Hello World</div>
	<v-skeleton  />
	<v-skeleton width="300px" height="50px" class="mt-5" />
	<v-skeleton width="300px" height="300px" type="circle" class="mt-5" />
</template>

<script lang="ts">
	import { defineComponent } from 'vue';

	export default defineComponent({
		setup() {
			return {};
		},
	});
</script>

<style scoped></style>
