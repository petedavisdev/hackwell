<template>
	<form :class="$style.box">
		<input
			id="food-2023-04-10T12:45"
			type="checkbox"
			:class="$style.edit"
		/>

		<label :class="$style.snack" for="food-2023-04-10T12:45">
			12:45 - 13:00
		</label>

		<section :class="$style.edit">
			<h3>Snack</h3>

			<Edit />

			<label :class="$style.box" for="food-2023-04-10T12:45">
				Save
			</label>
			Delete
		</section>
	</form>
</template>

<style module>
.box {
	font-family: monospace;
	margin: 0.5em;
	padding: 0.5em 1ch;
	text-align: center;
	background-color: transparent;
	color: SkyBlue;
	border: solid currentColor 2px;
	border-radius: 3px;
}

.edit {
	display: none;
}

:checked + .meal,
:checked + .snack {
	display: none;
}

:checked ~ .edit {
	display: grid;
}

.meal,
.snack {
	display: grid;
	grid-template-columns: 1fr auto 1fr;
}

.meal::before,
.snack::before {
	text-align: start;
}

.meal::before {
	content: 'Meal';
}

.snack::before {
	content: 'Snack';
}

.meal::after,
.snack::after {
	content: '+';
	text-align: end;
}

.snack,
.box:has(.snack),
.box:has(.snack) .box {
	color: HotPink;
}
</style>
