<script>
  import Tailwindcss from "./Tailwindcss.svelte";
  export let name;
</script>

<style>

</style>

<Tailwindcss />
<h1 class="uppercase tracking-wide text-sm text-indigo-600 font-bold">
  Hello {name}!
</h1>
