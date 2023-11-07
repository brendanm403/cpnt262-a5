<script>
export let title = "placeholder title";
export let description = "placeholder description for the card";
export let src = "placeholder src";
export let alt = "placeholder alt text for the card image";
export let href = "#";
</script>

<div class="w-fit">
  <a {href}>
    <article class=" rounded-xl border-2 border-black">
      <img class="block w-full rounded-t-xl" {src} {alt}>
      <h2 class="text-center text-2xl p-2 max-w-fit mx-auto">{title}</h2>
      <p class="w-80 p-2 mx-auto">{description}</p>
    </article>
  </a>
</div>

