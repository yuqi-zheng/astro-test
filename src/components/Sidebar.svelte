<script>
</script>

<aside>
  <nav>
    <!-- svelte-ignore a11y-no-redundant-roles -->
    <ul role="list">
      <li><a href="/services">Services</a></li>
      <li><a href="/about">About Us</a></li>
      <li><a href="/contact">Get Started</a></li>
    </ul>
  </nav>
</aside>

<style>
  aside {
    position:fixed;
    background-color: var(--clr-primary-800);
    overflow: hidden;
    width: 100%;
    height: 100%;
    z-index: 20;

    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 1.5em;
  }

  li a {
    font-family: 'Outfit', sans-serif;
    text-decoration: none;
    color: var(--clr-accent-200);
    font-size: 2.5em;
  }
</style>
