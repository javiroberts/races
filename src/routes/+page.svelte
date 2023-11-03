<script>
    import Tile from "$lib/tile.svelte";
</script>

<div class="h-screen bg-gradient-to-br from-purple-400 to-yellow-400 p-6">
    <h1 class="text-center text-5xl font-black text-neutral-50 underline decoration-4 decoration-yellow-400">
        Próximas Carreras
    </h1>

    <div class="columns-5 mx-32 mt-10">
        <Tile title="test-race" link="#" likeCount={12} />
        <Tile title="test-race" link="#" likeCount={11} />
        <Tile title="test-race" link="#" likeCount={10} />
        <Tile title="test-race" link="#" likeCount={9} />
        <Tile title="test-race" link="#" likeCount={8} />
        <Tile title="test-race" link="#" likeCount={7} />
        <Tile title="test-race" link="#" likeCount={6} />
        <Tile title="test-race" link="#" likeCount={5} />
        <Tile title="test-race" link="#" likeCount={4} />
    </div>
    
</div>

<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
        overflow: hidden;
        height: 100%;
    }
</style>