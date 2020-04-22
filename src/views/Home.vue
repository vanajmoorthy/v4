<template>
	<div class="home">
		<div class="container">
			<div class="column">
				<div class="content">
					<h1>Hi, I'm Vanaj Moorthy!</h1>
					<h2>
						I'm an 18 year old developer and artist from New Delhi.
					</h2>
					<h3>
						I'm an avid front-end web developer, a backend novice,
						and proficient digital artist. I enjoy making mostly
						inane but sometimes useful web projects and I love 3D
						art and motion graphics.
					</h3>
				</div>
			</div>
			<div class="column">
				<div class="imgcontainer">
					<img
						id="scooter"
						src="../assets/scooter.png"
						alt="scooter image"
					/>
				</div>
			</div>
		</div>

		<Footer></Footer>
	</div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
	name: "Home",
	components: {
		Footer
	}
};
</script>

<style scoped>

.content {
	padding-top: 100px;
  padding-bottom: 100px;
}

h1 {
	font-weight: 600;
	color: #576980;
	font-size: 38px;

}

h2 {
	font-weight: 500;
	color: #7f8c9c;
	width: 45%;
	font-size: 28px;
}

h3 {
	font-weight: 400;
	color: #576980;
	width: 60%;
	font-size: 22px;
	line-height: 24px;
}

.home {
	font-family: canada-type-gibson, sans-serif;
	font-style: normal;
}

.imgcontainer {
	text-align: center;
}

#scooter {
	height: 28rem;
	margin: auto;
}

.container {
	padding-left: 2rem;
	padding-right: 2rem;
	display: flex;
	align-items: center;
}

.column {
	flex: 1;
}
</style>
