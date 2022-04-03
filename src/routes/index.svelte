<script>
	import BannerComp from '$lib/Banner.svelte';
	import MainImageComp from '$lib/MainImageComp.svelte';

	import MissionComp from '$lib/MissionComp.svelte';
	// import MainVidComp from '$lib/SecondVidComp.svelte';
	import MainDivComp from '$lib/MainDivComp.svelte';

	import ReviewsComp from '$lib/ReviewsComp.svelte';
	import ReviewsFormComp from '$lib/ReviewsFormComp.svelte';
	// import SecondVidComp from '$lib/SecondVidComp.svelte';
	import FooterComp from '$lib/FooterComp.svelte';
	import NavButton from '$lib/images/NavButton.svelte';
	
    
</script>

<body>
	

	<BannerComp />
	<div class="revform">

		<MainImageComp />
		<MissionComp />

		<iframe width="335" height="595" src="https://www.youtube.com/embed/adLBtc5uBwM" 
			title="YouTube video player" frameborder="0" 
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
			allowfullscreen>
		</iframe>

		<iframe width="700" height="400" src="https://www.youtube.com/embed/M4ZGLJk7Cjw" 
			title="YouTube video player" frameborder="0" 
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
			allowfullscreen>
		</iframe>

		<MainDivComp />

		<iframe  width="700" height="400" src="https://www.youtube.com/embed/PHDLlOBqkjw"
			title="YouTube video player" frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
			allowfullscreen>
		</iframe>
		
		<ReviewsComp />
		<ReviewsFormComp />
		<NavButton />
	</div>
	<FooterComp />
	
</body>

<style>
	body {
		background-color: black;
	}

	.revform {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-evenly;
	}
</style>
