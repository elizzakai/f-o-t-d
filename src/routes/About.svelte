<script lang="ts">
	import Icons from './Icons.svelte';
</script>

<div>
	<div class="about-parent flex items-center p-4 pr-4 pl-10">
		<p class="about">
			Our main goal is to find good fanfic stories faster, so that people can read as much as they
			can optimally!
			<span class="block pb-4"></span>
			be able to search for fics like you do on the sites, -- tell the site what type of fic that you’re
			looking for (tags & all), and have the site find you a good fit of the day! (don’t like your fit?
			run again the randomizer to find another!
			<span class="block pb-4"></span>
			for the fic of the day (FOTD) -- get a good summary on what the fic is about, writing quality,
			length of the story, completed/not completed
		</p>

		<div class="flex flex-col gap-20">
			<Icons
				svg={`<svg xmlns="http://www.w3.org/2000/svg" width="115" height="84" viewBox="0 0 115 84" fill="none" class="icon-1">
	  <path d="M11.6901 3.85421C13.8194 4.18907 15.9487 4.52393 18.078 4.85879C21.4555 5.38994 24.9793 4.96275 28.3421 5.4916" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M10.7752 4.69189C10.0305 9.33996 9.84851 13.1561 9.59303 17.7543C9.3679 21.8059 9.34555 25.7627 9.36401 29.7399C9.38279 33.7854 8.89249 37.7462 8.61163 41.834C8.28959 46.5211 7.52087 50.9873 6.76707 55.6918C6.41198 57.9079 5.32503 64.0411 3.98121 64.9582" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M8.05112 34.6855L19.4732 36.4818" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M42.3791 7.20837C40.4238 6.90086 38.5309 10.6678 37.24 13.2969C34.8278 18.2101 32.6402 23.268 30.6661 28.7008C29.1455 32.8857 28.1431 37.5901 27.4131 42.1463C26.7709 46.154 25.6268 51.0063 26.1636 54.8165C27.0278 60.9506 30.0998 63.668 33.507 64.2038C36.5856 64.688 38.5367 66.6729 41.5819 62.5296C44.5734 58.4592 46.2227 52.9126 47.6439 47.0725C48.509 43.5172 49.6481 37.6449 49.6328 34.0279C49.6204 31.1121 49.0052 28.4956 48.9876 25.694C48.9717 23.1699 48.126 20.5158 47.4567 18.5565C46.9685 17.1274 46.4938 14.3185 45.8336 13.2581C45.0025 11.9234 43.8366 8.88495 43.4711 6.88942" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M59.4568 14.3101C67.0043 15.497 74.5167 16.6784 82.0472 17.8627" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M69.8637 15.947C67.0189 33.7013 63.6906 51.2254 60.8435 68.9938" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M89.1144 17.4419C88.2196 23.0261 87.3249 28.6104 86.4301 34.1947C85.5961 39.3995 85.3375 44.5884 84.6083 49.7619C83.9724 54.273 84.1498 58.9197 83.4242 63.4477C82.8048 67.3138 82.1853 71.1798 81.5659 75.0458" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M89.5973 16.5268C90.1564 14.6208 97.0896 20.9837 97.5576 21.4118C100.985 24.5472 103.352 28.297 105.573 32.2506C109.833 39.8351 109.466 49.3082 107.57 57.4463C106.277 62.9931 101.216 68.2728 96.3344 71.0193C93.9952 72.3354 91.5479 73.6398 89.0143 74.7307C87.8811 75.2187 86.4262 75.6371 85.2067 75.8751C84.3012 76.0518 83.6496 76.6945 82.6714 76.5406" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M12.773 67.8605C13.473 63.4921 10.9176 67.2384 13.3167 67.6157C13.9408 67.7139 15.4746 68.2689 15.8388 67.4986C16.5187 66.0603 15.1851 65.9278 14.1184 65.7601" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M47.6083 68.7148C47.3993 70.0191 48.4863 71.5687 50.0196 71.3877C50.2868 71.3562 50.7542 70.4538 50.6605 70.1857C50.4338 69.5363 49.4534 69.3353 48.8687 69.2433" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M72.157 72.9059C72.0441 73.6106 71.2988 74.765 71.9596 75.1869C72.8988 75.7865 73.5037 75.7044 74.5683 75.5788C75.1582 75.5091 75.563 74.2557 75.301 73.804C74.953 73.204 73.8247 72.8248 73.2442 72.4163" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M100.867 78.4116C100.371 81.5042 104.805 80.9811 103.819 78.8759" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	</svg>`}
			/>
			<Icons
				svg={`<svg xmlns="http://www.w3.org/2000/svg" width="118" height="86" viewBox="0 0 118 86" fill="none" class="icon-2">
	  <path d="M2.49032 23.1766C4.60036 22.7364 6.7104 22.2961 8.82045 21.8558C12.1673 21.1575 15.312 19.511 18.6444 18.8157" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M1.93106 24.2842C2.87922 28.8951 4.05941 32.5287 5.44752 36.9198C6.67065 40.7889 8.04987 44.4976 9.47447 48.2109C10.9236 51.9881 11.8665 55.8661 13.0503 59.7888C14.4077 64.2866 15.2691 68.7359 16.2287 73.4027C16.6808 75.6011 17.8344 81.7221 16.9021 83.0554" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M9.99656 53.3008L21.3153 50.9391" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M32.3808 15.4545C30.4431 15.8589 30.0056 20.0519 29.7286 22.9677C29.211 28.4166 28.9547 33.9213 29.0308 39.7011C29.0894 44.1533 29.8165 48.9081 30.7459 53.4278C31.5634 57.4034 32.2104 62.3467 34.0607 65.7204C37.0395 71.1519 40.8743 72.6064 44.2507 71.9019C47.3014 71.2653 49.8287 72.4314 51.2107 67.4787C52.5684 62.6131 52.1483 56.8417 51.4109 50.8765C50.962 47.2451 49.9496 41.3497 48.6553 37.9722C47.6119 35.2494 46.1106 33.0199 45.1028 30.4057C44.1948 28.0506 42.4647 25.8674 41.1454 24.2717C40.1831 23.1079 38.7451 20.6487 37.7524 19.8905C36.5028 18.9362 34.3372 16.5069 33.2892 14.7698" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M50.8665 16.0542C58.3457 14.4936 65.7901 12.9403 73.2524 11.3833" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M61.1792 13.9024C64.8009 31.5146 67.8888 49.0826 71.5134 66.7088" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M79.7134 8.48877C80.8526 14.0283 81.9917 19.5679 83.1308 25.1075C84.1926 30.2707 85.7868 35.2154 86.9354 40.3122C87.937 44.7565 89.7471 49.0397 90.6708 53.5316C91.4594 57.3666 92.248 61.2017 93.0367 65.0368" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M79.8413 7.46226C79.6899 5.48176 88.426 8.97961 89.0152 9.21443C93.33 10.9343 96.8711 13.6038 100.347 16.5158C107.015 22.1021 110.024 31.0921 111.131 39.3746C111.884 45.02 109.019 51.749 105.425 56.0452C103.703 58.1039 101.875 60.1898 99.8917 62.1067C99.0045 62.9641 97.7919 63.8702 96.7354 64.5244C95.951 65.0101 95.569 65.8417 94.5997 66.044" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M26.1521 82.659C25.261 78.3255 24.1966 82.7337 26.574 82.2377C27.1925 82.1086 28.8234 82.0849 28.8914 81.2356C29.0184 79.6498 27.7242 79.9978 26.6672 80.2184" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M59.0358 71.1313C59.3019 72.4252 60.8669 73.4899 62.2369 72.778C62.4757 72.654 62.5935 71.6446 62.4111 71.427C61.9692 70.8999 60.9811 71.0588 60.4017 71.1797" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M83.4792 66.3643C83.623 67.0634 83.3344 68.4067 84.1018 68.5675C85.1923 68.796 85.7291 68.5052 86.6803 68.011C87.2074 67.7371 87.1425 66.4215 86.7377 66.0918C86.1998 65.6537 85.0103 65.6983 84.3229 65.5216" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	  <path d="M112.28 61.355C112.91 64.4229 116.872 62.3646 115.205 60.7446" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
	</svg>`}
			/>
			<Icons
				svg={`<svg xmlns="http://www.w3.org/2000/svg" width="118" height="86" viewBox="0 0 118 86" fill="none" class="icon-2">
  <path d="M2.49032 23.1766C4.60036 22.7364 6.7104 22.2961 8.82045 21.8558C12.1673 21.1575 15.312 19.511 18.6444 18.8157" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M1.93106 24.2842C2.87922 28.8951 4.05941 32.5287 5.44752 36.9198C6.67065 40.7889 8.04987 44.4976 9.47447 48.2109C10.9236 51.9881 11.8665 55.8661 13.0503 59.7888C14.4077 64.2866 15.2691 68.7359 16.2287 73.4027C16.6808 75.6011 17.8344 81.7221 16.9021 83.0554" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M9.99656 53.3008L21.3153 50.9391" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M32.3808 15.4545C30.4431 15.8589 30.0056 20.0519 29.7286 22.9677C29.211 28.4166 28.9547 33.9213 29.0308 39.7011C29.0894 44.1533 29.8165 48.9081 30.7459 53.4278C31.5634 57.4034 32.2104 62.3467 34.0607 65.7204C37.0395 71.1519 40.8743 72.6064 44.2507 71.9019C47.3014 71.2653 49.8287 72.4314 51.2107 67.4787C52.5684 62.6131 52.1483 56.8417 51.4109 50.8765C50.962 47.2451 49.9496 41.3497 48.6553 37.9722C47.6119 35.2494 46.1106 33.0199 45.1028 30.4057C44.1948 28.0506 42.4647 25.8674 41.1454 24.2717C40.1831 23.1079 38.7451 20.6487 37.7524 19.8905C36.5028 18.9362 34.3372 16.5069 33.2892 14.7698" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M50.8665 16.0542C58.3457 14.4936 65.7901 12.9403 73.2524 11.3833" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M61.1792 13.9024C64.8009 31.5146 67.8888 49.0826 71.5134 66.7088" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M79.7134 8.48877C80.8526 14.0283 81.9917 19.5679 83.1308 25.1075C84.1926 30.2707 85.7868 35.2154 86.9354 40.3122C87.937 44.7565 89.7471 49.0397 90.6708 53.5316C91.4594 57.3666 92.248 61.2017 93.0367 65.0368" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M79.8413 7.46226C79.6899 5.48176 88.426 8.97961 89.0152 9.21443C93.33 10.9343 96.8711 13.6038 100.347 16.5158C107.015 22.1021 110.024 31.0921 111.131 39.3746C111.884 45.02 109.019 51.749 105.425 56.0452C103.703 58.1039 101.875 60.1898 99.8917 62.1067C99.0045 62.9641 97.7919 63.8702 96.7354 64.5244C95.951 65.0101 95.569 65.8417 94.5997 66.044" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M26.1521 82.659C25.261 78.3255 24.1966 82.7337 26.574 82.2377C27.1925 82.1086 28.8234 82.0849 28.8914 81.2356C29.0184 79.6498 27.7242 79.9978 26.6672 80.2184" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M59.0358 71.1313C59.3019 72.4252 60.8669 73.4899 62.2369 72.778C62.4757 72.654 62.5935 71.6446 62.4111 71.427C61.9692 70.8999 60.9811 71.0588 60.4017 71.1797" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M83.4792 66.3643C83.623 67.0634 83.3344 68.4067 84.1018 68.5675C85.1923 68.796 85.7291 68.5052 86.6803 68.011C87.2074 67.7371 87.1425 66.4215 86.7377 66.0918C86.1998 65.6537 85.0103 65.6983 84.3229 65.5216" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
  <path d="M112.28 61.355C112.91 64.4229 116.872 62.3646 115.205 60.7446" stroke="black" stroke-opacity="0.5" stroke-width="3" stroke-linecap="round"/>
</svg>`}
			/>
		</div>
	</div>
</div>

<style>
	@reference "tailwindcss";

	.about-parent {
		width: 781px;
		/* text-align: center; */
		/* padding-left: 500px; */
		margin: 0 auto;
		display: flex;
		/* display: inline-flex; */

		height: 695px;
		flex-direction: row;
		justify-content: center;

		align-items: center;
		gap: 40px;
		flex-shrink: 0;
	}

	.about {
		color: #000;
		font-family: Inter;
		font-size: 32px;
		font-style: normal;
		font-weight: 400;
		line-height: normal;
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
		padding-bottom: 90px;
	}

	.live:hover {
		color: rgb(159, 42, 178);
	}

	.icon-1 {
		width: 105.01px;
		height: 66.841px;
		transform: rotate(9.955deg);
		flex-shrink: 0;
	}

	.icon-2 {
		width: 105.01px;
		height: 66.841px;
		transform: rotate(-10.768deg);
		flex-shrink: 0;
	}
</style>
