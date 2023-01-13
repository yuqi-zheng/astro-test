<script>
  import "../styles/global.css";
</script>

<section>
  <h2>What's included?</h2>
  <div id="container">
    <div class="row">
      <div class="header">
        <img src="server.svg" alt="server icon" />
        <h3>Hosting Fees</h3>
      </div>
      <div class="text">All hosting and security (SSL) certificate costs</div>
    </div>
    <div class="row">
      <div class="header">
        <img src="write.svg" alt="writing icon" />
        <h3>Copywriting</h3>
      </div>
      <div class="text">
        Custom copywriting with SEO, including competitor analysis and keyword
        research
      </div>
    </div>
    <div class="row">
      <div class="header">
        <img src="draw.svg" alt="drawing icon" />
        <h3>Graphic Design</h3>
      </div>
      <div class="text">
        A hand-drawn logo, as well as custom graphics in the design.
      </div>
    </div>
    <div class="row">
      <div class="header">
        <img src="graph.svg" alt="graph icon" />
        <h3>Analytics</h3>
      </div>
      <div class="text">
        Website integration with Google Analytics, so you'll be up to date with
        all the stats.
      </div>
    </div>
    <div class="row">
      <div class="header">
        <img src="changes.svg" alt="cycle icon" />
        <h3>Free Changes</h3>
      </div>
      <div class="text">
        2 hours of free bonus development time every month for any website
        alterations you want to make
      </div>
    </div>
    <div class="row">
      <div class="header">
        <img src="support.svg" alt="support agent icon" />
        <h3>Support</h3>
      </div>
      <div class="text">Talk to real people, based in Melbourne</div>
    </div>
  </div>
</section>

<style>
  h2 {
    font-family: "Outfit", sans-serif;
    font-size: 2em;
    font-weight: var(--fw-medium);
    margin-bottom: 1em;
  }
  #container {
    background-color: var(--clr-primary-700);
    border: 2px solid var(--clr-primary-600);
    box-shadow: 0px 0px 24px 4px rgba(48, 52, 56, 0.25);
    width: 100%;
    border-radius: 10px;
    font-family: "Outfit", sans-serif;
    display: flex;
    gap: 1.5em;
    padding: 1.5em;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
  }

  .row {
    width: 100%;
    display: flex;
    justify-content: space-between;
    gap: 1.5em;
  }

  .header {
    display: flex;
    flex: 1 1 0px;
    justify-content: flex-start;
    align-items: center;
    gap: 1.5em;
    white-space: nowrap;
    background-color: #f7f5f3;
    border: 3px solid #9ba6ae;
    border-radius: 10px;
    padding-left: 1.5em;
    padding-right: 1.5em;
  }

  h3 {
    font-size: 2em;
    font-weight: var(--fw-medium);
  }

  .text {
    width: 60%;
    background-color: #f7f5f3;
    border: 3px solid #9ba6ae;
    border-radius: 10px;
    
    display: flex;
    flex: 2 2 0px;
    flex-direction: column;
    justify-content: center;
    padding: 1.5em;
    font-size: 1.25em;
    font-weight: var(--fw-medium);
  }

  @media screen and (max-width: 50em) {
    .row {
      flex-direction: column;
    }
    .text {
      width: 100%;
      font-size: 1em;
    }
    h3 {
      font-size: 1.5em;
    }

    .header {
      justify-content: center;
    }
    img {
      display: none;
    }
    .text {
      text-align: center;
    }
  }
</style>
