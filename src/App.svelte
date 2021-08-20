<script>
    import List from "./List.svelte";
    import Gerar from "./Gerar.svelte";
</script>

<main>
    <div class="is-size-1 has-text-centered my-4">
        <h1>Pass-Gen</h1>
        <p class="subtitle">Gerador de senhas fortes</p>
    </div>
    <div class="my-3">
        <Gerar />
    </div>
    <div class="my-3">
        <List />
    </div>
</main>
