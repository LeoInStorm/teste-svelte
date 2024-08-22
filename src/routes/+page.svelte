<script lang="ts">
    let count = 0;
</script>

<h1>Contador: {count}</h1>
<h2>isso é apenas um teste</h2>
<button on:click={() => count++}>Aumentar</button>
<button on:click={() => count--}>Diminuir</button>
<button on:click={() => count = count*2}>Dobrar</button>