<svelte:head>
	<title>About WFRecords</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<div id="miniNavBar">
		<nav>
			<ul>
				<li>
					<p>What Are We?</p>
				</li>
				<li>
					<p>Behind The Company</p>
				</li>
				<li>
					<p>What Do We Provide?</p>
				</li>
			</ul>
		</nav>
	</div>
	<div id="content">
		<div class="textContent" id="textV1">
			<h1>What is WFRecords?</h1>

			<h5>The Long:</h5>

			<p>
				WFRecords is a freelance company dedicated to all parts of the process of making auditory experiences for internet personalities.
				With a focus in music composition and production, WFRecords aims to equip streamers with the perfect ambience to their creations without
				having to worry about copyright issues plaguing them. 
			</p>

			<h5>The Short: </h5>

			<p>
				We make music you can use for streams, videos, and shorts specifically for you to use. 
			</p>
		</div>
		<div class="textContent" id="textV2">

		</div>
		<div class="textContent" id="textV3">

		</div>
	</div>
</div>

<style>
	nav {
		display: flex;
		justify-content: center;
		
	}
	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
		font-size: medium;
		margin: 35px;
	}

</style>