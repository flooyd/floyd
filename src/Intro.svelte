<script>
  import Collapse from "./Collapse.svelte";
</script>

<div class="container">
  <div class="intro">
    <header>
      <div class="title">Hi. This is my blog.</div>
      <div><Collapse /></div>
    </header>
    <p>More articles coming soon...</p>
    <header class="subheader">
      <div>About</div>
    </header>
    <p class="about">
      I am a UI developer. I enjoy <a href="https://svelte.dev/">Svelte</a> the
      most, followed by
      <a href="https://reactjs.org/">React</a>.
    </p>
    <p class="about">
      I enjoy CSS and JS in general, and on the backend, my favorite technology
      is
      <a href="https://nestjs.com/">NestJS</a>.
    </p>
    <p>This site was made with Svelte.</p>
    <header class="subheader">
      <div>Links</div>
    </header>
    <a class="links" href="https://github.com/flooyd">Github</a>
    <a class="links" href="https://www.linkedin.com/in/floyd-jones-2a51099a/"
      >LinkedIn</a
    >
  </div>
</div>

<style>
  .container {
    height: fit-content;
    background: var(--paradise-pink);
  }

  .intro {
    color: var(--cultured);
  }

  .title {
    font-style: italic;
  }

  .about a {
    display: inline-block;
    margin-bottom: 0px;
  }

  .links {
    padding-left: 8px;
  }
</style>
