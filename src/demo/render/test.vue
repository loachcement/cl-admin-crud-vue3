<template>
	<div>{{ value }}</div>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";

export default defineComponent({
	name: "test1",

	setup() {
		const value = ref<string>("Value：" + Math.random());

		return {
			value
		};
	}
});
</script>
