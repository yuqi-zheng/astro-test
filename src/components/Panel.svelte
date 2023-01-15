<script>
  import Card from "./Card.svelte";
</script>

<section>
  <h2><u>Everything</u> you need with no big upfront cost</h2>
  <div class="cards">
    <Card
      header="Design"
      text="No templates - we custom design your website from the ground up based on your needs.
    You give us as much detail as you want and we will do the rest."
      icon="palette.svg"
      second="Take a look at our gallery!"
    />
    <Card
      header="Develop"
      text="We hand-code each line to maximise performance. Lambda websites are built with industry leading web frameworks - optimised for
    minimal loading times."
      icon="keyboard.svg"
      second="Why should you care?"
    />
    <Card
      header="Maintain"
      text="We take care of any changes you want to make, and perform routine maintenance to keep your website
    running smoothly."
      icon="home_repair_service.svg"
      second="Small-business-friendly pricing"
    />
  </div>
</section>

<style>
  section {
    margin-bottom: 2em;
  }
  h2 {
    font-family: "Outfit", sans-serif;
    font-size: 2em;
    font-weight: var(--fw-medium);
    margin-bottom: 1.5em;
  }
  .cards {
    display: flex;
    justify-content: space-between;
    padding: 1.5em;
    gap: 1.5em;
    width: 100%;
    background-color: var(--clr-primary-700);
    border: 2px solid var(--clr-primary-700);
    box-shadow: 0px 0px 24px 4px rgba(48, 52, 56, 0.25);
    border-radius: 10px;
  }

  @media screen and (max-width: 50em) {
    .cards {
      flex-direction: column;
    }
  }
</style>
