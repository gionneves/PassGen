<script>
    let password = ["Passwords", "123456"];
</script>

<div id="List">
    {#each password as passwords}
        <div class="mx-5 my-2">
            <div class="box">
                <p>{passwords}</p>
            </div>
        </div>
    {/each}
</div>
