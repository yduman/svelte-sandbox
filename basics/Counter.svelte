<script>
  let count = 0;

  $: doubled = count * 2;
  $: quadrupled = doubled * 2;

  function handleClick() {
    count += 1;
  }
</script>

<button on:click={handleClick}>Clicked {count}</button>
<p>{count} doubled is {doubled}</p>
<p>{count} quadrupled is {quadrupled}</p>
