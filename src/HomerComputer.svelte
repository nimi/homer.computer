<script>
  import Prompt from "./Prompt.svelte"
  import Screen from "./Screen.svelte"
  import Monitor from "./Monitor.svelte"
  import Keyboard from "./Keyboard.svelte"
</script>

<style>
  main {
    background-color: rgb(190 178 165);
    display: flex;
    flex-direction: column;
    align-content: flex-start;
    height: 100%;
  }
</style>

<main>
  <Monitor>
    <Screen>
      <Prompt />
    </Screen>
  </Monitor>
  <Keyboard />
</main>
