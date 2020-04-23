/* eslint-disable */

<template>
	<div class="code">
		<div class="container">
			<div class="cards">
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Morph</span> 💠</h1>
						<p>
							A generative design system to create multi-coloured
							crystal graphics.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">cshell</span> 🐚</h1>
						<p>
							A simple Unix based LSH written in C that taught me
							the basics of a shell's life process.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Speechy</span> 🐢</h1>
						<p>
							This is a small LISP style programming language I
							made that transpiles to JavaScript.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Short</span> ✂️</h1>
						<p>
							This is a simple URL shortener I wrote using Express
							and MongoDB and hosted on Heroku.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Obstacles</span> ▶️</h1>
						<p>
							A super fun game I made using p5.js and all the free
							time I gained from bunking classes.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Tic Tac Toe</span> ❌</h1>
						<p>
							A tic tac toe game made using the minimax algorithm
							(which is annoyingly unbeatable) and vanilla
							JavaScript.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Pi2</span> 🥧</h1>
						<p>
							A truly awful pi approximation program I wrote using
							Leibniz's formula for finding pi.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">English2Yoda </span> 👽</h1>
						<p>
							A pretty simple English to Yodish translator I made
							using p5.js and an annoying amount of JavaScript.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Pi</span> 🥧</h1>
						<p>
							A physics simulation based on a 3Blue1Brown video
							that calculates pi using block collision.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Keylogger</span> 🕵️</h1>
						<p>
							A pretty simple keylogger made using Python, pyHook
							and pywin32.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Enigma</span> ❓</h1>
						<p>
							A remake of the German cryptography machine from
							World War II. Made using a Code Bullet video as a
							reference.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Spam Bot </span> 🤖</h1>
						<p>
							A WhatsApp spam bot made using Python and the
							Selenium web scraping library.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Visualise </span> 🎤</h1>
						<p>
							A sketch that generates balls which react to the
							sound input from your microphone.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Graph</span> 📈</h1>
						<p>
							A program that takes a mathematical function as
							input and plots it on a graph.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Paint</span> 🎨</h1>
						<p>
							A very buggy web remake of MSpaint.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">JockyCipher</span> 🔑</h1>
						<p>
							A dynamic ROT based cipher made using vanilla
							JavaScript.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Clock </span> 🕒</h1>
						<p>
							A simple graphical clock I implemented using a
							little bit of trigonometry and some bad colour
							choices.
						</p>
					</a>
				</div>
				<div class="card">
					<a href="https://google.com" target="_blank">
						<h1><span class="underline">Snake </span> 🍎</h1>
						<p>
							This is an emulation of the classic game snake in p5.js.
						</p>
					</a>
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
		Footer,
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

.code {
	font-family: canada-type-gibson, sans-serif;
	font-style: normal;
	font-weight: 500;
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

.container {
	margin: 2rem;
}
.cards {
	max-width: 1200px;
	margin: 0 auto;
	display: grid;
	grid-gap: 2rem;
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

@media (min-width: 600px) {
	.cards {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (min-width: 900px) {
	.cards {
		grid-template-columns: repeat(3, 1fr);
	}
}
</style>
