<script>
    import List from "./List.svelte";
    import Gerar from "./Gerar.svelte";
    let name = "Pass-Gen";
</script>

<main>
    <div class="text-center">
        <h1>Hello {name}</h1>
    </div>
    <Gerar />
    <List />
</main>
