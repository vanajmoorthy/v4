<template>
	<div class="wrapper">
		<footer class="footer">
			<div class="icon">
				<a href="https://www.behance.net/vanajmoorthy" target="_blank">
					<i class="fab fa-behance-square fa-lg"></i>
				</a>
			</div>
			<div class="icon">
				<a href="mailto:vanajmoorthy@gmail.com" target="_blank">
					<i class="fas fa-envelope fa-lg"></i>
				</a>
			</div>
			<div class="icon">
				<a href="https://github.com/vanajmoorthy" target="_blank">
					<i class="fab fa-github fa-lg"></i>
				</a>
			</div>
			<div class="icon">
				<a href="https://instagram.com/vanajmoorthy" target="_blank">
					<i class="fab fa-instagram fa-lg"></i>
				</a>
			</div>
			<div class="icon">
				<a href="https://twitter.com/vanajmoorthy" target="_blank">
					<i class="fab fa-twitter fa-lg"></i>
				</a>
			</div>
		</footer>
	</div>
</template>

<script>
export default {
	name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
	color: #576980;
}

a:hover {
	color: #2998c4;
	transition: all 0.3s ease;
}

.icon {
	display: inline;
	padding: 1.5em;
}

@media only screen and (max-width: 490px) {
	.icon {
		padding: 0.8em;
	}
}

.wrapper {
	display: flex;
	justify-content: center;
	align-items: center;
}

.footer {
	/* backdrop-filter: blur(2px); */
	padding: 10px 0 20px 0;
	display: flex;
	/* flex: 0.5; */
	justify-content: space-evenly;
	height: 9vh;
	width: 30%;
	color: #576980;
	text-align: center;
}
</style>
