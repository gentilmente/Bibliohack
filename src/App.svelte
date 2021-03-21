<script>
  import Frame from "./Frame.svelte";
  export let name;
  //import "./booth.js";
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>We came to solve your digitalization process</p>
  <Frame />
</main>

<style>
  main {
    font-family: "Satisfy", Helvetica, cursive;
    text-shadow: 1px 1px 7px black;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
