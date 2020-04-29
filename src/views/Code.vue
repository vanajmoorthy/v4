/* eslint-disable */

<template>
	<div class="code">
		<div class="container">
			<div class="cards">
				<Card
					title="Morph "
					emoji="💠"
					desc="A generative design system to create multi-coloured
							crystal graphics."
					link="https://vanajmoorthy.com/morph"
				></Card>

				<Card
					title="cshell "
					emoji="🐚"
					desc="A simple Unix based LSH written in C that taught me
							the basics of a shell's life process."
					link="https://vanajmoorthy.com/gh/cshell"
				></Card>

				<Card
					title="Speechy "
					emoji="🐢"
					desc="This is a small LISP style programming language I
							made that transpiles to JavaScript."
					link="https://vanajmoorthy.com/gh/speechy"
				></Card>

				<Card
					title="Short "
					emoji="✂️"
					desc="This is a simple URL shortener I wrote using Express
							and MongoDB and hosted on Heroku."
					link="http://vanaj.me"
				></Card>

				<Card
					title="Obstacles "
					emoji="▶️"
					desc="A super fun game I made using p5.js and all the free
							time I gained from bunking classes."
					link="https://vanajmoorthy.com/obstacles"
				></Card>

				<Card
					title="Tic Tac Toe "
					emoji="❌"
					desc="A tic tac toe game made using the minimax algorithm
							(which is annoyingly unbeatable) in vanilla
							JavaScript."
					link="https://vanajmoorthy.com/tictactoe"
				></Card>

				<Card
					title="Pi2 "
					emoji="🥧"
					desc="A truly awful pi approximation program I wrote using
							Leibniz's formula for finding pi."
					link="https://vanajmoorthy.com/pi2"
				></Card>

				<Card
					title="Yoda "
					emoji="👽"
					desc="A pretty simple English to Yodish translator I made
							using p5.js and an annoying amount of JavaScript."
					link="https://vanajmoorthy.com/yoda"
				></Card>

				<Card
					title="Pi "
					emoji="🥧"
					desc="A physics simulation based on a 3Blue1Brown video
							that calculates pi using block collision."
					link="https://vanajmoorthy.com/pi"
				></Card>

				<Card
					title="Keylogger "
					emoji="🕵️"
					desc="A pretty simple keylogger made using Python, pyHook
							and pywin32."
					link="https://vanajmoorthy.com/gi/keylogger"
				></Card>

				<Card
					title="Enigma "
					emoji="❓"
					desc="A remake of the German cryptography machine from
							World War II. Made using a Code Bullet video as a
							reference."
					link="https://vanajmoorthy.com/enigma"
				></Card>

				<Card
					title="Spam Bot "
					emoji="🤖"
					desc="A WhatsApp spam bot made using Python and the
							Selenium web scraping library."
					link="https://vanajmoorthy.com/gh/spambot"
				></Card>

				<Card
					title="Visualise "
					emoji="🎤"
					desc="A sketch that generates balls which react to the
							sound input from your microphone."
					link="https://vanajmoorthy.com/visualise"
				></Card>

				<Card
					title="Graph "
					emoji="📈"
					desc="A program that takes a mathematical function as
							input and plots it on a graph."
					link="https://vanajmoorthy.com/graph"
				></Card>

				<Card
					title="Paint "
					emoji="🎨"
					desc="A very buggy web remake of MSpaint."
					link="https://vanajmoorthy.com/paint"
				></Card>

				<Card
					title="JockyCipher "
					emoji="🔑"
					desc="A dynamic ROT based cipher made using vanilla
							JavaScript."
					link="https://vanajmoorthy.com/jockycipher"
				></Card>

				<Card
					title="Clock "
					emoji="🕒"
					desc="A simple graphical clock I implemented using a
							little bit of trigonometry and some bad colour
							choices."
					link="https://vanajmoorthy.com/clock"
				></Card>

				<Card
					title="Snake "
					emoji="🍎"
					desc="This is an emulation of the classic game snake in p5.js."
					link="https://vanajmoorthy.com/snake"
				></Card>
			</div>
		</div>
		<Footer></Footer>
	</div>
</template>

<script>
import Footer from "@/components/Footer.vue";
import Card from "@/components/Card.vue";
export default {
	name: "Home",
	components: {
		Footer,
		Card,
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
