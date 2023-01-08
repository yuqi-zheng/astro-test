<script>
  import "../styles/global.css";
</script>

<div id="hero">
  <div id="hero-left">
    <p class="tag">Reach new horizons.</p>
    <p id="expand">
      We build and maintain high performance websites for small businesses, at
      an affordable monthly cost.
    </p>
    <button href="/contact"
      >let's get started! <img src="send-dark.svg" alt=" " /></button
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
    width: 100%;
    height: 450px;
  }

  #hero-left {
    box-sizing: border-box;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    width: 50%;
    height: 450px;
    background-color: rgba(39, 41, 74, 0.8);
    backdrop-filter: blur(5px);
    padding: 24px 48px 64px 48px;
  }

  .tag {
    color: #f7f5f3;
    font-family: "Outfit", sans-serif;
    font-size: 72px;
    font-weight: 900;
  }

  #expand {
    font-family: "Outfit", sans-serif;
    font-weight: 400;
    color: #f7f5f3;
    font-size: 18px;
    width: 80%;
  }

  button {
    box-sizing: border-box;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    align-items: center;
    padding: 12px 32px;
    width: 275px;
    height: 55px;
    isolation: isolate;
    font-family: "Outfit", sans-serif;
    color: #27294a;
    font-weight: 400;
    font-size: 24px;
    white-space: nowrap;

    border: 2px solid #f3e9ac;
    border-radius: 50px;

    background: linear-gradient(to left, #f3e9ac 50%, #eec447 50%) right;
    background-size: 200%;
    transition: 0.2s ease-out;
  }

  button:hover {
    background-position: left;
    border: 2px solid #ea8827;
  }

  button:hover img {
      transform: scale(0.8);
      transition: 0.2s ease-in-out;
  }

  .wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    pointer-events: none;
  }
</style>
