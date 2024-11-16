<script>
function redirect(url) {
  window.location.href = `${url}`;
}
</script>

<main>
  <div>
  </div>
  <nav>
    <button on:click={redirect("https://discord.gg/T4CUhhcdzh")}>Discord</button>
  </nav>
  <h1>Welcome!</h1>

  <p>
    I have loads of projects, like Simple Essentials and more!
  </p>

  <button on:click={redirect("https://github.com/SimpleDevMCBE")}>Github</button>
  <button on:click={redirect("https://mcpedl.com/user/amethystdev")}>MCPEDL</button>
  <button on:click={redirect("https://simple.amethystdev.com")}>Simple Essentials</button>

  <p class="read-the-docs">
    I love little kids
  </p>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
