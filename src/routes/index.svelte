<script>

	import MainImageComp from '$lib/MainImageComp.svelte';

	import MissionComp from '$lib/MissionComp.svelte';
	import MainVidComp from '$lib/SecondVidComp.svelte';
	import MainDivComp from '$lib/MainDivComp.svelte';

	import ReviewsComp from '$lib/ReviewsComp.svelte';
	import ReviewsFormComp from '$lib/ReviewsFormComp.svelte';
	import SecondVidComp from '$lib/SecondVidComp.svelte';
	import FooterComp from '$lib/FooterComp.svelte';

    
</script>

<body>
	

	
	<div class="revform">
		<MainImageComp />
		<MissionComp />
		<MainVidComp /> 

		<MainDivComp />
		<SecondVidComp />
		<ReviewsComp />
		
		<ReviewsFormComp />
		
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
		justify-content: center;
	}
</style>
