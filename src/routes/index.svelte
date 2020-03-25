<script>
  import { pageTitle } from "../store";
</script>

<style>

</style>

<svelte:head>
  <title>{$pageTitle}</title>
</svelte:head>

<h1>{$pageTitle}</h1>
