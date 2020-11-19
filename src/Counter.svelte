<script>
  export  let counter = 0

    function increment() {
        counter++;
    }

    function decrement() {
        counter--;
    }

</script>

<div class="flex flex-col space-y-2 items-center">
    <h1>{counter}</h1>
    <button class="btn"
            on:click={increment}>Svelet +
    </button>
    <button class="btn"
            on:click={decrement}>TailwindCSS -
    </button>
</div>
