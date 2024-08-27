<script lang="ts">
    import Cabecalho from "$lib/components/Cabecalho.svelte";
    import Rodape from "$lib/components/Rodape.svelte";
import "../app.css"
</script>
<Cabecalho/>
<slot></slot>
<Rodape/>