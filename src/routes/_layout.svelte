<script>
	export let segment;
</script>

<main>
	{segment || ''}
	<div class="content">
		<slot></slot>
	</div>
</main>

<style lang="scss" global>
	@import "../scss/index.scss";
</style>