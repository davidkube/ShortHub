
<script lang="ts">
    import Match from "$lib/components/display/matches/Match.svelte";
    import type {matches} from '@prisma/client';
    export let matches: Array<matches>;
</script>

<div class="md:container flex justify-center space-x-4 
            bg-base-100 rounded-box overflow-x-scroll px-10 py-2">
    {#each matches as match}
        <Match match={match}/>
    {/each}
</div>