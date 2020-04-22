<template>
	<footer class="footer">
		<div class="icon">
			<i class="fab fa-behance-square fa-lg"></i>
		</div>
		<div class="icon">
			<i class="fas fa-envelope fa-lg"></i>
		</div>
		<div class="icon">
			<i class="fab fa-github fa-lg"></i>
		</div>
		<div class="icon">
			<i class="fab fa-instagram fa-lg"></i>
		</div>
		<div class="icon">
			<i class="fab fa-twitter fa-lg"></i>
		</div>
	</footer>
</template>

<script>
export default {
	name: "Footer"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

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
	position: fixed;
	left: 0;
	height: 9vh;
	bottom: 0;
	width: 100%;
	color: #576980;
	text-align: center;
}
</style>
