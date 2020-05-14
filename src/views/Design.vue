<template>
	<div class="design">
		<div class="container">
			<h1>
				Coming soon, for now you can go to
				<router-link to="/">home</router-link>.
			</h1>
		</div>
		<Footer></Footer>
	</div>
</template>

<script>
export default {
	name: "Design",
};
</script>

<style scoped>
a {
	color: #2998c4;
}
.container {
	display: flex;
	padding: 0 2rem;
	justify-content: center;
	align-items: center;
	height: 75vh;
}
h1 {
	font-family: canada-type-gibson;
	font-weight: 500;
	color: #576980;
	text-align: center;
}
</style>
