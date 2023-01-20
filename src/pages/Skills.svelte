<script>
	import Card from '../components/Card.svelte';
	const skills = [
		{
			icon: 'vscode-icons:file-type-js-official',
			label: 'JavaScript'
		},
		{
			icon: 'file-icons:tsx-alt',
			label: 'TypeScript'
		},
		{
			icon: 'skill-icons:angular-light',
			label: 'Angular'
		},
		{
			icon: 'skill-icons:react-dark',
			label: 'React'
		},
		{
			icon: 'fa-brands:node',
			label: 'Node'
		},
		{
			icon: 'logos:aws',
			label: 'AWS'
		},
		{
			icon: 'skill-icons:sass',
			label: 'Sass'
		},
		{
			icon: 'simple-icons:styledcomponents',
			label: 'Styled components'
		},
		{
			icon: 'skill-icons:postgresql-light',
			label: 'Postgresql'
		},
		{
			icon: 'logos:mysql',
			label: 'MySQL'
		},
		{
			icon: 'mdi:git',
			label: 'Git'
		},
		{
			icon: 'logos:python',
			label: 'Python'
		}
	];
</script>

<section>
	<h1>SKILLS</h1>
	<ul>
		{#each skills as { icon, label }, i}
			<Card {icon} {label} />
		{/each}
	</ul>
</section>

<style>
	section {
		text-align: center;
		display: flex;
		flex-direction: column;
		padding: 5vw;
		align-items: center;
		max-width: 100vw;
	}
	ul {
		list-style-type: none;
		display: flex;
		flex-wrap: wrap;
	}
</style>
