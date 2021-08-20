<script>
    let password = ["Passwords", "123456"];
</script>

<div id="List">
    {#each password as passwords}
        <div class="box">
            <p>{passwords}</p>
        </div>
    {/each}
</div>
