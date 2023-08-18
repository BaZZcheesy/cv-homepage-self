<script>
  let name = "Ian";
  let age = 18


const increaseAge = () => {
  age++;
}

const decreaseAge = () => {
  age--;
}

</script>

<main>
  <h1>Svelte</h1>

  <p>{name}</p>
  <p>{age}</p>
  <button on:click={decreaseAge}>Decrease Age</button>
  <button on:click={increaseAge}>Increase Age</button>
</main>