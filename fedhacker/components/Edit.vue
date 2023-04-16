<template>
	<div>
		<input :class="$style.input" value="12" />:<input
			:class="$style.input"
			value="45"
		/>
		-
		<input :class="$style.input" value="13" />:<input
			:class="$style.input"
			value="00"
		/>
	</div>
</template>

<style module>
.input {
	font-family: monospace;
	margin: 0.5em;
	padding: 0.5em 1ch;
	text-align: center;
	background-color: transparent;
	color: white;
	border: solid currentColor 2px;
	border-radius: 3px;
	width: 5ch;
}
</style>
