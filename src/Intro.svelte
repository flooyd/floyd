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
    <header class="subheader">
      <div>About</div>
    </header>
    <p class="about">
      I am a UI developer. I enjoy <a href="https://svelte.dev/">Svelte</a> the
      most, followed by
      <a href="https://reactjs.org/">React</a>. I enjoy CSS and JS in general,
      and on the backend, my favorite technology is
      <a href="https://nestjs.com/">NestJS</a>.
    </p>
    <p>This site was made with Svelte.</p>
    <header class="subheader">
      <div>Links</div>
    </header>
    <p>
      <a href="https://github.com/flooyd">Github</a>
      <a href="https://www.linkedin.com/in/floyd-jones-2a51099a/">LinkedIn</a>
    </p>
  </div>
</div>

<style>
  .container {
    height: fit-content;
    min-width: 48%;
    flex-grow: 100;
    background: var(--paradise-pink);
  }

  .intro {
    color: var(--cultured);
  }

  header div:first-of-type {
    font-style: italic;
  }

  .about a {
    display: inline-block;
  }
</style>
