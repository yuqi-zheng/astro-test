<script>
  export let text;
  export let icon;
  export let header;
  export let second;
</script>

<article class="card">
  <div class="header">
    <h4>{header}</h4>
    <img src={icon} alt="icon" />
  </div>
  <div class="text">
    <p>{text}</p>
  </div>
  <div class="bottom">
    <p>{second}</p>
    <img class="arrow" src="arrow.svg" alt="arrow" />
  </div>
</article>

<style>
  .card {
    box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
    /* width: calc(100%/3); */
    background-color: var(--clr-neutral-50);
    border: 3px solid var(--clr-neutral-300);
    border-radius: 10px;
    padding: 1em;

    display: flex;
    flex: 1 1 0px;
    flex-direction: column;
    justify-content: space-between;
    gap: 1em;
    font-family: "Outfit", sans-serif;
  }

  h4 {
    font-size: var(--fs-500);
    font-weight: var(--fw-medium);
  }

  .text {
    font-size: var(--fs-400);
    font-weight: var(--fw-regular);
    color: var(--clr-neutral-950);
  }

  .header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .bottom {
    justify-self: flex-end;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    font-weight: var(--fw-semibold);
    font-size: 1em;
    gap: 1em;
    transition: all 0.2s;
  }

  .bottom:hover {
    transform: translateX(-2%);
  }
</style>
