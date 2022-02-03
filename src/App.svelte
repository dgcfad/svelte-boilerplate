<script lang="ts">
  const title = 'Svelte boilerplate';
</script>

<main>
  <h1>{title}</h1>
</main>

<style lang="scss" global>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  $heading: #2249b4;

  h1 {
    color: $heading;
  }
</style>
