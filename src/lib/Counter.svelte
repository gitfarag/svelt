<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  increment
  
</button>
<button on:click={()=>count > 0 ? count-=1 : ''}>
  decrement
  
</button>
<button on:click={()=>count=0}>reset</button>
count is {count}
