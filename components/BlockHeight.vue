<template>
	{{ value < 0 ? '???' : value.toLocaleString() }}
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
	props: {
		value: Number,
	},
});

</script>

