<script>
	import Icon from '@iconify/svelte';
</script>

<footer>
	<div class="col-md-12">
		<div class="link">
			<a href="https://www.linkedin.com/in/esther-cec%C3%ADlia-oliveira-528464183/"
				><Icon icon="uiw:linkedin" style="font-size: 1em" color="white" /></a
			>
			<a href="https://github.com/EstherCecilia"
				><Icon icon="jam:github" style="font-size: 1em" color="white" /></a
			>
		</div>
		<div class="copyright py-4 text-center">
			<div class="container">
				<small>
					Copyright &copy;{' '}
					Esther Cecília
				</small>
			</div>
		</div>
	</div>
</footer>

<style>
	footer {
		background-color: #7f7f7f;
		display: flex;
		justify-content: center;
	}

	.link {
		display: flex;
		justify-content: center;
		margin-top: 30px;
		font-size: 22px;
	}

	.link > a {
		margin: 0 0.5em;
	}
</style>
