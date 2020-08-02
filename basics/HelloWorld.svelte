<script>
  import Description from "./Description.svelte";
  import Counter from "./Counter.svelte";

  let name = "Leeroy Jenkins";
</script>

<style>
  h1 {
    color: purple;
    font-size: 2em;
  }
</style>

<h1>Hello {name}!</h1>
<Description />
<Counter />
