<script>
  import GlobalStyles from "./global-styles.svelte";
  import onInterval from "./hooks/on-interval";

  const titles = ["software engineer", "human", "reader", "friend"];
  let titleIndex = 0;

  onInterval(() => {
    titleIndex = (titleIndex + 1) % titles.length;
  }, 3000);
</script>

<style>
  .wrapper {
    height: 100%;
  }
</style>

<GlobalStyles />
<div class="wrapper">
  <h1>b. cedric cogell</h1>
  <p>{titles[titleIndex]}</p>
</div>
