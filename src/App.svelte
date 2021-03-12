<script lang="ts">
  export let name: string = 123;
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte
    apps.
  </p>
</main>

<style type="less">
  @primary: #f44336;

  @keyframes fade {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  main {
    display: flex;
    align-items: center;
    justify-content: center;
    max-width: 240px;
    margin: 0 auto;
    padding: 1em;
    text-align: center;
  }

  h1 {
    color: @primary;
    font-weight: 100;
    font-size: 4em;
    text-transform: uppercase;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
