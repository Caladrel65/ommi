<script>
	import coloring from '$lib/images/coloring.jpeg';
</script>

<svelte:head>
	<title>Curriculum | Ozark Mountain Massage Institute</title>
</svelte:head>

<div class="container">
	<header>
		<h1>Curriculum</h1>
	</header>

	<h2>Graduation Requirements</h2>
	<p>
		To successfully graduate from Ozark Mountain Massage Institute, students must meet the following
		criteria:
	</p>
	<ul>
		<li>
			Complete a minimum of 500 hours of the approved curriculum, which includes both lecture and
			hands-on technique training.
		</li>
		<li>
			Pass all chapter exams, the mid-term examination, and the final examination with a minimum
			grade of 70%.
		</li>
		<li>Fulfill all financial obligations to the Institute.</li>
		<li>Comply with all attendance and conduct policies throughout the program.</li>
	</ul>
	<p>
		Only students who meet all of these requirements will be eligible to receive a certificate of
		graduation.
	</p>

	<div class="image-container">
		<img src={coloring} alt="Student coloring anatomical diagrams" class="curriculum-image" />
	</div>
</div>

<style>
	.container {
		max-width: 800px;
		margin: 0 auto;
		padding: 2em;
	}

	.image-container {
		margin-top: 2em;
		display: flex;
		justify-content: center;
	}

	.curriculum-image {
		width: 100%;
		max-width: 100%;
		height: auto;
		border-radius: 15px;
	}

	header {
		text-align: center;
		margin-bottom: 2em;
	}

	h1 {
		font-size: 2.5em;
	}

	h2 {
		font-size: 1.8em;
		margin-top: 1.5em;
	}
</style>
