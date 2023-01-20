<script>
	import Icon from '@iconify/svelte';
	/**
	 * @type {string}
	 */
	export let icon;
	/**
	 * @type {string}
	 */
	export let label;
</script>

<li class="list-inline-item mx-3">
	<span
		><div class="skills-tile">
			<Icon {icon} style="font-size: 3em" />

			<p class="text-center" style="font-size: 30%; margin-top: 4px;">{label}</p>
		</div></span
	>
</li>

<style>
	li {
		padding: 1em;
		max-width: 10em;
		display: flex;
		flex-direction: column;
		align-items: center;
		margin: 0 3em;
	}

	.skills-tile {
		background-color: rgba(248, 245, 244, 0.05);
		padding: 10px 10px 5px;
		width: 100px;
		margin: 5px 0;
		border-radius: 8px;
		text-align: center !important;
	}
</style>
