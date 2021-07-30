<template>
	<h3>Your score is {{ score }}</h3>
</template>

<script>
export default {
  props: ["score"],
}
</script>

<style scoped>
	h3 {
		color: red;
		font-weight: bold;
	}
</style>
