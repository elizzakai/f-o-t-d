<script lang="ts">
	let props = $props();
</script>

<div class="header-box">
	<section class="header">
		<section class="title-box">
			<h2 class="t-header">{props.title}</h2>
		</section>
		<section class="title-description">
			<p class="t-describe">
				{@html props.description}
			</p>
		</section>
	</section>
</div>

<style>
	@reference "tailwindcss";

	.t-describe :global(.live:hover) {
		color: rgb(159, 42, 178);
	}

	.about {
		width: 621px;
		//padding-top: 100px;
		display: inline-flex;
		height: 695px;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 40px;
		flex-shrink: 0;
	}

	.header {
		display: flex;
		width: 993px;
		padding: 0px 100px;
		align-items: flex-start;
		gap: 40px;
	}

	.title-box {
		display: flex;
		padding: 0px 7px;
		flex-direction: column;
		align-items: flex-start;
		gap: 10px;
		border-radius: 7px;
		background-color: #fed7c2;
	}

	.t-header {
		color: #000;
		/* h2 */
		font-family: 'Space Grotesk';
		font-size: 40px;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
	}

	.t-describe {
		color: #000;
		font-family: Inter;
		font-size: 32px;
		font-style: normal;
		font-weight: 400;
		line-height: normal;
	}

	.title-description {
		width: 580px;
		flex-shrink: 0;
		color: #000;
		/* p */
		font-family: 'Space Grotesk';
		font-size: 18px;
		font-style: normal;
		font-weight: 400;
		line-height: normal;
	}

	.header-box {
		display: flex;
		width: 1440px;
		padding: 0px 100px;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 40px;
		padding-top: 130px;
		padding-bottom: 40px;
	}

	.live:hover {
		color: rgb(159, 42, 178);
	}
</style>
