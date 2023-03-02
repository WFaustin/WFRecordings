<script>
	import Header from './Header.svelte';
	import './styles.css';
    import TopNavbar from './top-navbar.svelte';
</script>

<div class="app">
	<Header />
	<TopNavbar />

	<main>
		<slot />
	</main>

</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}



	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}

	slot{
		justify-content: center;
	}
</style>
