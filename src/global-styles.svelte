<style>
  /* flow height thru html document */
  :global(html),
  :global(body) {
    height: 100%;
  }

  :global(body) {
    /* system fonts */
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
      Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
      "Segoe UI Symbol";
    /* remove default spacing */
    margin: 0;
    padding: 0;
  }

  /* border box sizing  */
  :global(html) {
    box-sizing: border-box;
  }
  :global(*),
  :global(*:before),
  :global(*::after) {
    box-sizing: inherit;
  }

  /* default flex  */
  :global(div) {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>


