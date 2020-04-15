// eslint-disable

<template>
	<div id="app">
		<div id="nav">
			<router-link to="/">
				<span id="fulltext">
					<span id="vanaj">Vanaj</span>
					<span id="moorthy"> Moorthy</span>
				</span>
				<span id="shorttext">
					<span id="vanaj">V</span>
					<span id="moorthy">M</span>
				</span>
			</router-link>
			<ul>
				<li><router-link to="/code">Code</router-link></li>
				<li><router-link to="/work">Work</router-link></li>
				<li><router-link to="/design">Design</router-link></li>
			</ul>
		</div>
		<router-view />
	</div>
</template>

<style>

body {
	background-color: #f7fafc;
}

</style>

<style scoped>

#shorttext {
	display: none;
}
@media only screen and (max-width: 494px) {
	#shorttext {
		display: block;
	}
	#fulltext {
		display: none;
	}
}

#nav a.router-link-exact-active {
	text-decoration: underline !important;
}

a {
	text-decoration: none;
	color: #576980;

}


#vanaj {
	color: #2998c4;
}

#nav {
	font-family: canada-type-gibson, sans-serif;
	font-weight: 600;
	font-style: normal;
	max-width: 100vw;
	height: 13vh;
	margin: 0 2rem;
	display: flex;
	align-items: center;
	justify-content: space-between;
	font-size: 1.3rem;
}

ul {
	padding: 0;
	font-weight: 400;
	list-style-type: none;
	margin: 0;
	cursor: default;
	text-align: center;
}

li {
	padding: 0;
	margin: 0;
	display: inline-block;
	margin-left: 25px;
	cursor: pointer;
	user-select: none;
	transition: all 0.3s ease-out;
}

@media only screen and (max-width: 385px) {
	li {
		margin-left: 17px;
	}
}

@media only screen and (max-width: 360px) {
	li {
		margin-left: 10px;
	}
}

@media only screen and (max-width: 320px) {
	li {
		margin-left: 7px;
	}
}

a:hover {
	color: #2998c4;
	transition: all 0.3s ease;
}
</style>
