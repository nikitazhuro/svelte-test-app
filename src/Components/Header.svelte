<script>
  let counter = 0;

  function handleClickIncrease() {
    counter += 1 
  };

  function handleClickDecrease() {
    counter -= 1 
  };

</script>

<div>
  <span class="counter">Now, count is = {counter}</span>

  <div class="btns">
    <button class="btn" on:click={handleClickIncrease}>Increase</button>
    <button class="btn" on:click={handleClickDecrease}>Decrease</button>
  </div>
</div>

<style>
  .btn {
    padding: 5px 10px;
    color: #fff;
    background: teal;
    border-radius: 5px;
    margin: 5px;
  }
  .counter {
    color: burlywood;
  }
</style>