<script>
  export let name;
</script>

<main>
  <h1>Welcome!</h1>
  <p>this is my world.</p>
  <p>do you know what youve gotten yourself into?</p>
  <div class="footer">
    <i>living life lentilly since 1999</i>
  </div>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
    background-color: #a3b18a;
    color: #344e41;
    height: 100vh;
  }

  h1 {
    color: #772e25;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 400;
  }

  .footer {
    display: inline-block;
    padding: 2em;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
