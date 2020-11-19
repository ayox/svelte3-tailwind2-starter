<script>
    export let name;
</script>

<style type="text/scss">
  $color: red;

  h1 {
    color: $color;
  }

  h1 {
    @apply bg-black text-white;
  }
</style>


<div class="space-y-10 flex items-center flex-col mb-3">
    <h1 class="header">Hello {name}!</h1>

    <p>SASS is working!</p>

<button class="btn"> Also <code>@apply</code> is working </button>
</div>

