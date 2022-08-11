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
    flex-wrap: wrap;
    justify-content: center;
    gap: 13px;
    padding: 20px;
    background: var(--cultured);
    font-family: "Open Sans", sans-serif;
  }
</style>
