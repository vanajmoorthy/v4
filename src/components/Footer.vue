<template>
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
</template>

<script>
export default {
	name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

a {
  color: #576980
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

.footer {
	/* backdrop-filter: blur(2px); */
	padding-top: 40px;
	/* position: fixed; */
	display: inline;
	height: 9vh;
	width: 100%;
	color: #576980;
	text-align: center;
}
</style>
