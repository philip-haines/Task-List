<template>
	<header>
		<h1>Task Tracker</h1>
		<Button text="Add Tast" color="green" />
	</header>
</template>

<script>
import Button from "./Button";

export default {
	name: "Header",
	props: {
		title: {
			type: String,
		},
	},
	components: {
		Button,
	},
};
</script>

<style scoped>
header {
	display: flex;
	justify-content: space-between;
	align-items: center;
	margin-bottom: 3rem;
}
</style>
