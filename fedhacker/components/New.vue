<template>
	<footer :class="$style.new">
		<Fed />
		<Fed />
	</footer>
</template>

<style module>
.new {
	display: grid;
	grid-template-columns: 1fr 1fr;
	margin-right: 5ch;
}
</style>
