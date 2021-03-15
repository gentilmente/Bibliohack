<script>
  import Frame from "./Frame.svelte";
  export let name;
  //import "./booth.js";
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
  <Frame />
</main>

<style>
</style>
