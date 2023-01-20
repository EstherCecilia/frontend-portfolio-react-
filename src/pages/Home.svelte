<script>
	const professions = ['FRONT-END DEVELOPER', 'BACK-END DEVELOPER', 'DEV TEAM LEAD'];
	let profession = professions[0];
	let interator = 0;

	const setProfession = (/** @type {number} */ index) => {
		setTimeout(() => {
			profession = professions[index];
			if (index === 2) {
				interator = 0;
			} else {
				interator += 1;
			}
			setProfession(interator);
		}, 3000);
	};

	setProfession(interator + 1);
</script>

<section>
	<svg
		xmlns="http://www.w3.org/2000/svg"
		xmlns:xlink="http://www.w3.org/1999/xlink"
		aria-hidden="true"
		focusable="false"
		width="1em"
		height="1em"
		preserveAspectRatio="xMidYMid meet"
		viewBox="0 0 32 32"
		class="iconify header-icon"
		data-icon="la:laptop-code"
		data-inline="false"
		style="transform: rotate(360deg);"
		><path
			fill="currentColor"
			d="M5 6v13.563l-2.281 2.314A2.444 2.444 0 0 0 2 23.594A2.418 2.418 0 0 0 4.406 26h23.188A2.418 2.418 0 0 0 30 23.594a2.45 2.45 0 0 0-.719-1.719L27 19.562V6H5zm2 2h18v11H7V8zm9 1l-1.5 9H16l1.5-9H16zm-3.914 2l-1.719 2.068L10 13.5l.367.432L12.086 16l1.086-.863L11.81 13.5l1.36-1.637L12.087 11zm7.828 0l-1.086.863L20.19 13.5l-1.36 1.637l1.085.863l1.719-2.068L22 13.5l-.367-.432L19.914 11zM6.437 21h19.125l2.313 2.281a.464.464 0 0 1 .125.313a.386.386 0 0 1-.406.406H4.406A.386.386 0 0 1 4 23.594c0-.11.047-.234.125-.313L6.438 21z"
		/></svg
	>
	<h1>Esther Cecília</h1>
	<div class="c1" />
	<span class="profession">
		{profession}
	</span>
</section>

<style>
	section > .header-icon {
		height: 150px;
		width: 150px;
	}

	section {
		padding: 20vw;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.c1 {
		display: inline-block;
	}

	.profession {
		text-align: center;
		max-width: 16em;
		color: #fff;
		font-family: monospace;
		overflow: hidden; /* Ensures the content is not revealed until the animation */
		border-right: 0.15em solid orange; /* The typwriter cursor */
		white-space: nowrap; /* Keeps the content on a single line */
		margin: 0 auto; /* Gives that scrolling effect as the typing happens */
		letter-spacing: 0.15em; /* Adjust as needed */
		animation: typing 3s steps(30, end), blink-caret 0.1s step-end infinite;
		animation-iteration-count: infinite;
	}

	/* The typing effect */
	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}

	/* The typewriter cursor effect */
	@keyframes blink-caret {
		from,
		to {
			border-color: transparent;
		}
		50% {
			border-color: orange;
		}
	}
</style>
