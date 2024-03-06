<script>
  let count = 0;

  function handleClick() {
    count += 1;
  }
</script>

<button on:click={handleClick}>
  Clicked {count}
  {count === 1 ? "time" : "times"}
</button>
<p>Here is the count value: {count}</p>

<style>
  p {
    display: grid;
    color: orangered;
    font-weight: 500;
    font-size: 23px;
    font-family: "Courier New", Courier, monospace;
  }
</style>
