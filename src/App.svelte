<script>
  import Tip from "./components/tip/tip.svelte";

  import First from "./components/first.svelte";
  import Second from "./components/second.svelte";
  import Third from "./components/third.svelte";
</script>

<style type="text/scss">
  .content {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto 100px;
    &__header {
      color: #ff3e00;
      text-transform: uppercase;
      font-size: 4em;
      font-weight: 100;
    }
  }

  :global(h1) {
    font-size: 22px;
    text-transform: capitalize;
  }
  :global(html) {
    --color-grey: #aeaeae;
  }
</style>

<main class="content">
  <h1 class="content__header">Hello user!</h1>
  <p>
    Visit my
    <a href="https://svelte.dev/tutorial">Svelte article</a>
    to see the basic guide :).
  </p>

</main>

<Tip />
<First />
<Second />
<Third />
