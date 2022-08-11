<script lang="ts">
  import Articles from "./Articles.svelte";
  import Intro from "./Intro.svelte";
  import Nav from "./Nav.svelte";
</script>

<Nav />
<main>
  <Intro />
  <Articles />
</main>

<style>
  main {
    height: calc(100% - 99px);
    display: flex;
    padding: 20px;
    background: var(--cultured);
    font-family: "Open Sans", sans-serif;
  }
</style>
