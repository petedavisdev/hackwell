<script setup>
onMounted(() => {
	var element = document.getElementById('main');
	element.scrollTop = element.scrollHeight;
});
</script>

<template>
	<main id="main">
		<article class="log">
			<h2>Monday</h2>

			<div>
				<time class="morethan12">12h</time>

				<form class="input">
					<input
						id="food-2023-04-10T14:48"
						class="edit"
						type="checkbox"
					/>
					<label class="meal" for="food-2023-04-10T14:48">
						08:00 - 08:15
					</label>

					<section class="edit">
						<h3>Meal</h3>
						<div>
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="00"
							/>
							-
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="15"
							/>
						</div>
						<label class="input" for="food-2023-04-10T14:48">
							Save
						</label>
						Delete
					</section>
				</form>

				<time class="morethan3">4h 30m</time>

				<form class="input">
					<input
						id="food-2023-04-10T12:45"
						class="edit"
						type="checkbox"
					/>
					<label class="snack" for="food-2023-04-10T12:45">
						12:45 - 13:00
					</label>

					<section class="edit">
						<h3>Snack</h3>
						<div>
							<input class="hour input" value="12" />:<input
								class="minute input"
								value="45"
							/>
							-
							<input class="hour input" value="13" />:<input
								class="minute input"
								value="00"
							/>
						</div>
						<label class="input" for="food-2023-04-10T12:45">
							Save
						</label>
						Delete
					</section>
				</form>
			</div>
		</article>

		<article class="log">
			<h2>Tuesday</h2>

			<div>
				<time class="morethan12">12h</time>

				<form class="input">
					<input
						id="food-2023-04-11T14:48"
						class="edit"
						type="checkbox"
					/>
					<label class="meal" for="food-2023-04-11T14:48">
						08:00 - 08:15
					</label>

					<section class="edit">
						<h3>Meal</h3>
						<div>
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="00"
							/>
							-
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="15"
							/>
						</div>
						<label class="input" for="food-2023-04-11T14:48">
							Save
						</label>
						Delete
					</section>
				</form>

				<time class="morethan3">4h 30m</time>

				<form class="input">
					<input
						id="food-2023-04-11T12:45"
						class="edit"
						type="checkbox"
					/>
					<label class="snack" for="food-2023-04-11T12:45">
						12:45 - 13:00
					</label>

					<section class="edit">
						<h3>Snack</h3>
						<div>
							<input class="hour input" value="12" />:<input
								class="minute input"
								value="45"
							/>
							-
							<input class="hour input" value="13" />:<input
								class="minute input"
								value="00"
							/>
						</div>
						<label class="input" for="food-2023-04-11T12:45">
							Save
						</label>
						Delete
					</section>
				</form>
			</div>
		</article>

		<article class="log">
			<h2>Yesterday</h2>
			<div>
				<time class="morethan12">12h</time>

				<form class="input">
					<input
						id="food-2023-04-12T14:48"
						class="edit"
						type="checkbox"
					/>
					<label class="meal" for="food-2023-04-12T14:48">
						08:00 - 08:15
					</label>

					<section class="edit">
						<h3>Meal</h3>
						<div>
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="00"
							/>
							-
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="15"
							/>
						</div>
						<label class="input" for="food-2023-04-12T14:48">
							Save
						</label>
						Delete
					</section>
				</form>

				<time class="morethan3">4h 30m</time>

				<form class="input">
					<input
						id="food-2023-04-12T12:45"
						class="edit"
						type="checkbox"
					/>
					<label class="snack" for="food-2023-04-12T12:45">
						12:45 - 13:00
					</label>

					<section class="edit">
						<h3>Snack</h3>
						<div>
							<input class="hour input" value="12" />:<input
								class="minute input"
								value="45"
							/>
							-
							<input class="hour input" value="13" />:<input
								class="minute input"
								value="00"
							/>
						</div>
						<label class="input" for="food-2023-04-12T12:45">
							Save
						</label>
						Delete
					</section>
				</form>
			</div>
		</article>

		<article class="log">
			<h2>Today</h2>

			<div>
				<time class="morethan12">12h</time>

				<form class="input">
					<input
						id="food-2023-04-13T14:48"
						class="edit"
						type="checkbox"
					/>
					<label class="meal" for="food-2023-04-13T14:48">
						08:00 - 08:15
					</label>

					<section class="edit">
						<h3>Meal</h3>
						<div>
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="00"
							/>
							-
							<input class="hour input" value="08" />:<input
								class="minute input"
								value="15"
							/>
						</div>
						<label class="input" for="food-2023-04-13T14:48">
							Save
						</label>
						Delete
					</section>
				</form>

				<time class="morethan3">4h 30m</time>

				<form class="input">
					<input
						id="food-2023-04-13T12:45"
						class="edit"
						type="checkbox"
					/>
					<label class="snack" for="food-2023-04-13T12:45">
						12:45 - 13:00
					</label>

					<section class="edit">
						<h3>Snack</h3>
						<div>
							<input class="hour input" value="12" />:<input
								class="minute input"
								value="45"
							/>
							-
							<input class="hour input" value="13" />:<input
								class="minute input"
								value="00"
							/>
						</div>
						<label class="input" for="food-2023-04-13T12:45">
							Save
						</label>
						Delete
					</section>
				</form>

				<time class="morethan2">2h 19m 20s</time>
			</div>

			<footer>
				<label class="meal input">&nbsp;</label>
				<label class="snack input">&nbsp;</label>
			</footer>
		</article>
	</main>
</template>

<style>
* {
	box-sizing: border-box;
}

body {
	display: grid;
	align-content: space-around;
	text-align: center;
	font-family: monospace;
	color: white;
	background-color: #012;
}

main {
	overflow-y: scroll;
	height: 100dvh;
}

article {
	padding: 0.5em calc(50dvw - 180px);
}

article:last-of-type {
	padding-bottom: 1em;
}

article:nth-child(odd) {
	background-color: #123;
}

article > div {
	margin-right: 5ch;
}

footer {
	display: grid;
	grid-template-columns: 1fr 1fr;
	margin-right: 5ch;
}

span {
	text-align: left;
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

time {
	font-size: large;
	color: tomato;
}

.morethan1 {
	color: orange;
}

.morethan2 {
	color: gold;
}

.morethan3 {
	color: greenYellow;
}

.morethan12 {
	color: paleGreen;
}

time::before,
time::after {
	display: block;
}

time::before {
	content: '▲';
}

time::after {
	content: '▼';
}

.input {
	font-family: monospace;
	margin: 0.5em;
	padding: 0.5em 1ch;
	text-align: center;
	background-color: transparent;
	color: SkyBlue;
	border: solid currentColor 2px;
	border-radius: 3px;
}

.hour,
.minute {
	width: 5ch;
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

.snack,
.input:has(.snack),
.input:has(.snack) .input {
	color: HotPink;
}

h2 {
	position: sticky;
	top: 0;
	float: right;
	margin: 0.5em;
	padding-inline: 0.25em;
	writing-mode: vertical-lr;
}
</style>
