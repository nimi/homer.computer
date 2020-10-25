<script>
  function handleKeyPress() {
    console.log("keypress");
  }
</script>

<style>
  .prompt {
    color: rgb(116, 238, 157);
    font-family: "IBM Plex Mono", monospace;
    font-size: 2rem;
    margin: 0;
    text-transform: uppercase;
    max-width: 250px;
  }
</style>

<p class="prompt" on:keydown={handleKeyPress}>To start{'\n'} press any key</p>
