<script>
  import Collapse from "./Collapse.svelte";
</script>

<div class="container">
  <div class="intro">
    <header>
      <div>Posts</div>
      <div><Collapse /></div>
    </header>
    <p class="clickable">The first article</p>
    <p class="clickable">The second article</p>
    <p class="clickable">How to make this blog</p>
  </div>
</div>

<style>
  .container {
    height: fit-content;
    background: var(--cadet-blue-crayola);
  }

  .intro {
    color: var(--cultured);
  }
</style>
