<script>
    import { Hamburger } from 'svelte-hamburgers';
    import Menu from './Sidebar.svelte';
    import { isSidebarOpen } from '../stores/sidebarStore.js';

    function toggleSidebar(state) {
      isSidebarOpen.set(!state);
      document.body.classList.toggle('lock-scroll');
    }

</script>

<header>
  <nav>
    <a href="/"><img src="logo-stacked.svg" alt="LOGO" /></a>
    <ul>
      <li><a href="/about">about</a></li>
      <li><a href="/services">services</a></li>
    </ul>
    <a id="button" href="/contact">contact us!<img src="send.svg" alt="" /></a>
    <div id="burger"><Hamburger type='squeeze' --layer-height=0.18em --layer-spacing=0.3em on:click={toggleSidebar($isSidebarOpen)}/>
    </div>
  </nav>  
  {#if $isSidebarOpen}
    <Menu />
  {/if}
</header>

<style>
  .locked {
    position: relative;
    overflow-y: hidden;
  }
  header {
    width: 100%;
  }
  nav {
    background-color: var(--clr-neutral-50);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2em 3em;
    box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
  }

  ul {
    height: 100%;
    display: flex;
    justify-content: flex-start;
    gap: 4em;
    align-items: center;
  }
  li {
    list-style: none;
  }
  li a {
    text-decoration: none;
    color: black;
    font-family: "Outfit", sans-serif;
    font-size: 1.25em;
    font-weight: var(--fw-regular);
  }
  #button {
    /* position */
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.5em 2em;
    border-radius: 50px;
    width: 10.5em;

    /* colour */
    color: white;
    background: linear-gradient(to left, var(--clr-primary-600) 50%, var(--clr-primary-700) 50%) right;
    background-size: 200%;
    transition: .2s ease-out;
    border: 1px solid var(--clr-primary-500);

    white-space: nowrap;
    isolation: isolate;

    /* font */
    font-weight: var(--fw-medium);
    font-family: "Outfit", sans-serif;
    font-size: 1.25em;
    text-decoration: none;
  }

  #button:hover {
    background-position: left;
  }

  #button:hover img {
      transform: scale(0.8);
      transition: 0.2s ease-in-out;
  }

  #burger {
    display: none;
  }

  img {
    max-width: 10em;
  }

  @media screen and (max-width: 50em) {
    ul, #button {
      display: none;
    }

    #burger {
      display: block;
    }

    img {
      transform: scale(0.75);
    }

    nav {
      padding: 0.5em 0.5em;
    }
  }
  
</style>
