<template>
	<div class="card">
		<a v-bind:href="link" target="_blank">
			<h1>
				<span class="underline">{{ title }}</span
				><span class="emoji">{{ emoji }}</span>
			</h1>
			<p>{{ desc }}</p>
		</a>
	</div>
</template>

<script>
export default {
	name: "Card",
	props: {
		title: String,
		emoji: String,
		desc: String,
		link: String,
	},
};
</script>

<style scoped>
.underline {
	text-decoration: underline;
}
a {
	text-decoration: none;
}
h1 {
	font-weight: 600;
	color: #576980;
	font-size: 30px;
	margin-top: 0.5rem;
}

p {
	color: #7f8c9c;
	margin-top: 1rem;
	margin-bottom: 1rem;
}

.card {
	background-color: white;
	color: white;
	padding: 1.8rem;
	position: relative;
	height: 8rem;
	border-radius: 12px;
	-webkit-box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.4);
	-moz-box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.4);
	box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.4);
	transition: 0.2s ease;
}
.card:hover {
	transform: translate(0, -10px);
	-webkit-box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.7);
	-moz-box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.7);
	box-shadow: 6px 25px 48px -19px rgba(153, 153, 153, 0.7);
}
</style>
