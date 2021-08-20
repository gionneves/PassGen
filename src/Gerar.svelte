<script>
    let inputPass;
</script>

<div id="Gerar">
    <div class="container">
        <div class="has-text-centered mx-6">
            <input
                bind:value={inputPass}
                class="input"
                type="text"
                id="getpass"
                name="getpass"
            />
        </div>
        <div class="has-text-right">
            <button class="button is-primary px-5 my-1 mx-6">Gerar</button>
        </div>
    </div>
</div>
