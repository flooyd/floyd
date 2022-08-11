<script>
  import Collapse from "./Collapse.svelte";
</script>

<div class="container">
  <div class="intro">
    <header>
      <div>Hi. This is my blog.</div>
      <div><Collapse /></div>
    </header>
    <p>More articles coming soon...</p>
  </div>
</div>

<style>
  .container {
    height: fit-content;
    min-width: 48%;
    flex-grow: 100;
    background: var(--cadet-blue-crayola);
  }

  .intro {
    color: var(--cultured);
  }

  header div:first-of-type {
    font-style: italic;
  }
</style>
