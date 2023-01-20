<script>
	import Icon from '@iconify/svelte';
</script>

<section>
	<h1>ABOUT ME</h1>

	<div class="container">
		<div class="polaroid">
			<img
				src="https://media.licdn.com/dms/image/D4D03AQHHP8u7FWnC0Q/profile-displayphoto-shrink_200_200/0/1673135105356?e=1679529600&v=beta&t=FWK0i9CGsLZPEywU0vjloHaLTqEJ0Q93aut6YvSKMCE"
				alt=""
			/>
			<div class="actions">
				<Icon icon="skill-icons:react-dark" style="font-size: 2.5em" />

				<Icon icon="file-icons:tsx-alt" style="font-size:  2.5em" />

				<Icon icon="vscode-icons:file-type-node2" style="font-size:  2.5em" />
			</div>
		</div>

		<div class="card">
			<div class="card-header">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					aria-hidden="true"
					focusable="false"
					width="1em"
					height="1em"
					preserveAspectRatio="xMidYMid meet"
					viewBox="0 0 64 64"
					class="iconify"
					data-icon="emojione:red-circle"
					data-inline="false"
					style="transform: rotate(360deg);"><circle cx="32" cy="32" r="30" fill="#ed4c5c" /></svg
				>
				&nbsp;
				<svg
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					aria-hidden="true"
					focusable="false"
					width="1em"
					height="1em"
					preserveAspectRatio="xMidYMid meet"
					viewBox="0 0 36 36"
					class="iconify"
					data-icon="twemoji:yellow-circle"
					data-inline="false"
					style="transform: rotate(360deg);"><circle cx="18" cy="18" r="18" fill="#FDCB58" /></svg
				>
				&nbsp;
				<svg
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					aria-hidden="true"
					focusable="false"
					width="1em"
					height="1em"
					preserveAspectRatio="xMidYMid meet"
					viewBox="0 0 36 36"
					class="iconify"
					data-icon="twemoji:green-circle"
					data-inline="false"
					style="transform: rotate(360deg);"><circle cx="18" cy="18" r="18" fill="#78B159" /></svg
				>
			</div>
			<div class="card-body" style="height: auto; font-size: 132%; line-height: 200%;">
				<br /><span class="wave">Hi :) </span><br /><br />👋 Hello I'm 21 years old and I'm
				passionate about technology and I'm currently a software engineer, specialized in front-end,
				with a deep knowledge in programming logic and with excellent learning and communication
				skills. Thank you 💜
			</div>
		</div>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		padding: 5vw;
		background-color: #7f7f7f;
		align-items: center;
	}

	section > h1 {
		margin-bottom: 4rem;
	}

	.polaroid {
		background: #6d6d6d;
		display: inline-block;
		margin: 55px 75px 30px;
		padding: 15px 15px 30px;
		text-align: center;
		text-decoration: none;
		box-shadow: 0 4px 6px rgb(0 0 0 / 30%);
		transition: all 0.2s linear;
		z-index: 0;
		position: relative;
	}

	.container {
		display: flex;
		justify-content: space-between;
		width: 100%;
	}
	.card {
		max-width: 45vw;
		position: relative;
		display: flex;
		flex-direction: column;
		min-width: 0;
		word-wrap: break-word;
		background-color: #6d6d6d;
		background-clip: border-box;
		border: 1px solid rgba(0, 0, 0, 0.125);
		border-radius: 0.25rem;
	}

	.card-header {
		padding: 0.75rem 1.25rem;
		margin-bottom: 0;
		background-color: rgba(0, 0, 0, 0.03);
		border-bottom: 1px solid rgba(0, 0, 0, 0.125);
	}
	.card-body {
		flex: 1 1 auto;
		min-height: 1px;
		padding: 1.25rem;
		margin-right: 1rem !important;
		margin-left: 1rem !important;
		text-align: justify !important;
		font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial,
			sans-serif;
	}

	.actions {
		margin-top: 5em;
	}
</style>
