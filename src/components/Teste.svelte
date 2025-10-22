<script>
    import { Button } from "$lib/components/ui/button";

    let count = $state(0);

    function increment() {
        count += 1;
    }
</script>

<h1>{count}</h1>
<Button variant="destructive" onclick={increment}>Add</Button>