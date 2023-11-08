<script>
export let title = "placeholder title";
export let description = "placeholder description for the card";
export let src = "placeholder src";
export let alt = "placeholder alt text for the card image";
export let href = "#";
export let release = "placeholder date"
</script>

<div class="w-fit">
  <a {href}>
    <article class="rounded-lg border-2 border-black hover:scale-105 active:scale-100">
      <img class="block w-full rounded-t-lg" {src} {alt}>
      <h2 class="text-center text-2xl p-2 max-w-fit mx-auto my-2">{title}</h2>
      <p class="w-16 mx-auto text-white bg-black p-1 rounded-3xl text-sm text-center my-3">{release}</p>
      <p class="w-80 p-2 mx-auto">{description}</p>
    </article>
  </a>
</div>