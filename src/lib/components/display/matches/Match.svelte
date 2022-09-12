<script lang="ts">
    import Card from "$lib/components/display/Card.svelte";
    import type {matches} from '@prisma/client';
    export let match: matches;
    
</script>

<Card
    desc={match.h.title}
    result={match.goals}
    xG={match.xG}
/>