<script>
    let count = $state(0);

    function increment() {
        count += 1;
    }
</script>

<h1>{count}</h1>
<button onclick={increment}>Add</button>