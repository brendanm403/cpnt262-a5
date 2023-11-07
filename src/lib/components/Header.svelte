<script>
  const navLinks = [
    {name: "Home", href: "/"},
    {name: "Albums", href: "/albums"},
    {name: "Merch", href: "/merch"}
  ]  
</script>

<header class="bg-gray-400 p-5">
  <nav class="flex justify-center">
    <ul class="flex">
      {#each navLinks as {name, href}}
        <li class="mx-4"><a class="p-2" {href}>{name}</a></li>
      {/each}
    </ul>
  </nav>
</header>