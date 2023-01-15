<script>
</script>

<div id="hero">
  <div id="hero-left">
    <div id="text">
      <p class="tag">Your new digital partner.</p>
      <p id="expand">
        We build and maintain high performance websites for small businesses, at
        an affordable monthly cost.
      </p>
    </div>
    <a class="button" href="/contact"
      >let's get started! <img src="send-dark.svg" alt=" " /></a
    >
  </div>
  <img class="wave" src="wave.svg" alt=" " />
</div>

<style>
  #hero {
    position: relative;
    background-image: url("hero.webp");
    background-size: cover;
    background-repeat: no-repeat;
    height: 35em;
    width: 100%;
  }

  #hero-left {
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    width: 50%;
    max-width: 50em;
    height: 35em;
    background-color: rgba(39, 41, 74, 0.8);
    backdrop-filter: blur(5px);
    padding: 1em 2.5em 4em 2.5em;
  }

  .tag {
    color: #f7f5f3;
    font-family: "Outfit", sans-serif;
    font-size: 4em;
    font-weight: var(--fw-black);
  }

  #text {
    display: flex;
    flex-direction: column;
  }

  #expand {
    font-family: "Outfit", sans-serif;
    font-weight: var(--fw-medium);
    color: #f7f5f3;
    font-size: 1.25em;
    width: 75%;
  }

  .button {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    align-items: center;
    font-size: 1.5em;
    gap: 0.5em;
    padding: 0.4em 2em;
    width: 12em;
    text-decoration: none;
    font-family: "Outfit", sans-serif;
    color: #27294a;
    font-weight: var(--fw-medium);
    white-space: nowrap;
    border: 2px solid #f3e9ac;
    border-radius: 4em;
    background: linear-gradient(to left, #f3e9ac 50%, #eec447 50%) right;
    background-size: 200%;
    transition: 0.2s ease-out;
  }

  .button:hover {
    background-position: left;
    border: 2px solid #ea8827;
  }

  .button:hover img {
    transform: scale(0.8);
    transition: 0.2s ease-in-out;
  }

  .wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    pointer-events: none;
  }

  @media screen and (max-width: 50em) {
    #hero-left {
      width: 100%;
      align-items: center;
      gap: 1em;
      padding: 2em 1.5em 2em 1.5em;
    }
    .wave {
      display: none;
    }
    #expand {
      width: 100%;
    }

    #text {
      gap: 4em;
    }

    .tag {
      font-size: 3em;
      text-align: center;
    }
  }

  @media screen and (min-width: 150em) {
    .wave {
      display: none;
    }
  }
</style>
