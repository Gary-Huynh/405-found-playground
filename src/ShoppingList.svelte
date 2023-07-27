<script>
    let items = [{name: "bananas", qty: 4}, {name: "rice", qty: 1}, {name: "chicken", qty: 2},{name: "onions", qty: 5}]
</script>

<h1>Shopping list</h1>
<ul>
  {#each items as item}
    <li>{item.name} x {item.qty}</li>
  {/each}
</ul>

<style>
    li {
      color: red;
    }
</style>