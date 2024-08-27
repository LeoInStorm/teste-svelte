<script lang="ts">
import Titulo from "$lib/components/Titulo.svelte";

    let count = 0;
</script>

<body>

    <Titulo tag='h1'>Contador: {count}</Titulo>
    <h2>isso é apenas um teste</h2>
    <button on:click={() => count++}>Aumentar</button>
    <button on:click={() => count--}>Diminuir</button>
</body>
