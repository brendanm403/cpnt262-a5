<script>
  import {albumData} from "../../lib/data.js"
  import Card from "../../lib/components/Card.svelte";
</script>

<!-- loop through data to render each card -->
<main class="flex justify-center flex-wrap gap-20 p-10">
  {#each albumData as albumCard}
    <Card {...albumCard}/>
  {/each}
  
</main>