<script lang="ts">
	import type {MatchesGoals, MatchesXG} from '@prisma/client';
    export let desc: String;
    export let result: MatchesGoals;
    export let xG: MatchesXG;
</script>

<div class="min-w-1/4 card w-96 bg-base-100 shadow-xl image-full">
	<figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
	<div class="card-body">
		<h2 class="card-title">{desc}</h2>
		<p>{result}</p>
		<div class="card-actions justify-end">
			<button class="btn btn-primary">{xG}</button>
		</div>
	</div>
</div>
