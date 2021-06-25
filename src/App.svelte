<script lang="ts">
	import Logo from "./components/Logo.svelte";
</script>

<body>
	<main>
		<div>
			<a href="https://instagram.com/schillig_dessau">
				<Logo/>
			</a>
		</div>
	</main>
</body>

<style lang="scss" global>
	@import "./styles/_styles.scss";

	div {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}

	a {
		max-width: 50vw
	}
</style>