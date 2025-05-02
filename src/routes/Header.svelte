<script lang="ts">
</script>

<nav class="nav-bar">
	<a href="/" class="nav nav-fotd space">FOTD</a>
	<a href="/about" class="nav nav-about">About us</a>
</nav>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Space+Grotesk:wght@370&display=swap');

	.inter {
		font-family: 'Inter', sans-serif;
		font-optical-sizing: auto;
		font-style: normal;
	}

	.space {
		font-family: 'Space Grotesk', sans-serif;
		font-optical-sizing: auto;
		font-style: normal;
	}

	.nav-fotd {
		width: 63px;
		height: 29px;
		color: #000;
		font-family: 'Space Grotesk';
		font-size: 21px;
		font-style: normal;
		font-weight: 700;
		line-height: normal;
		letter-spacing: 0.63px;
	}

	.nav-about {
		color: #000;
		font-family: 'Space Grotesk';
		font-size: 20px;
		font-style: normal;
		font-weight: 400;
		line-height: 28px; /* 140% */
		width: auto;
		height: auto;
	}

	a:hover {
		color: rgba(248, 136, 77, 1);
	}

	.nav-bar {
		display: flex;
		width: 1440px;
		padding: 0px 100px;
		justify-content: space-between;
		align-items: center;
		padding-top: 30px;
	}
</style>
