<template>
	<main :class="$style.main">
		<Day />
		<New />
	</main>
</template>

<style module>
.main {
	height: 100dvh;
	overflow-y: auto;
}
</style>
