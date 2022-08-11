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
    height: calc(100% - 26px);
    min-width: 48%;
    flex-grow: 100;
    background: var(--paradise-pink);
  }

  .intro {
    color: var(--cultured);
  }
</style>
