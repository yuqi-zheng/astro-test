<script>
</script>

<section>
  <img src="/logo-stacked.svg" alt="" />
  <br />
  <h1>Your new digital partner</h1>
  <p>We are an emerging digital media team based in Melbourne.</p>
  <p>
    We introduce the use of cutting-edge software to build high-performing
    websites for small businesses.
  </p>
  <br />
  <div id="features">
    <div class="feature">
      <img src="/brush-temp.svg" alt="" />
      <p>
        No templates — custom designed from the ground up based on your needs
      </p>
    </div>
    <div class="feature">
      <img src="/code-temp.svg" alt="" />
      <p>Hand-coded line by line, using industry leading web frameworks</p>
    </div>
    <div class="feature">
      <img src="/maintain-temp.svg" alt="" />
      <p>Includes maintenance and free monthly changes</p>
    </div>
  </div>
  <br />
  <h2>Pricing</h2>
  <p>
    We are currently offering lifetime discounted rates for our early bird
    clients.
  </p>
  <br />
  <div id="pricing">
    <p class="small" id="starting">Starting at</p>
    <div id="numbers">
      <p id="from-to"><s>$189</s><img src="/arrow-right.svg" alt="to" />$129</p>
      <p class="small" id="month">/month</p>
    </div>
  </div>
  <p>Currently <b>2</b> spots remaining</p>
  <br />
  <h3 id="secure">Secure your spot now:</h3>
  <br />
  <form name="Form" method="POST" data-netlify="true">
    <label
      ><p>Name</p>
      <input name="name" type="text" required /></label
    >
    <label
      ><p>Business Name</p>
      <input name="business-name" type="text" required /></label
    >
    <label
      ><p>Email</p>
      <input name="email" type="email" required /></label
    >
    <label
      ><p>How can we help?</p>
      <textarea
        name="project-desciption"
        type="text"
        rows="10"
        required
      /></label
    >
    <button type="submit">Submit</button>
  </form>
  <br />
  <br />
  <p>Full website coming soon...</p>
  <br />
  <a
    id="privacy"
    href="/lambda-privacy-policy.pdf"
    download="Lambda_Digital_Privacy_Policy">Privacy Policy</a
  >
</section>

<style>
  section {
    font-family: Outfit, sans-serif;
    font-size: var(--fs-400);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 1em;
    align-items: center;

    text-align: center;

    margin: 0 auto;
    max-width: 80em;
    padding: 1em;
  }
  #features {
    display: flex;
    justify-content: space-between;
  }

  .feature {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5em;
    width: 25%;
  }

  #pricing {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-size: var(--fs-500);
  }

  #numbers {
    display: flex;
    justify-content: space-between;
    gap: 0.1em;
  }

  #from-to {
    display: flex;
    justify-content: space-between;
    gap: 0.25em;
  }

  #starting {
    align-self: flex-start;
  }

  #month {
    align-self: flex-end;
    transform: translateY(-6px);
  }

  .small {
    font-size: var(--fs-300);
  }

  form {
    display: flex;
    flex-direction: column;
    gap: 1.5em;
    width: 50em;
  }

  input:focus,
  textarea:focus {
    outline: 2px solid #5539cd;
    border: none;
    border-radius: 10px;
  }

  input,
  textarea {
    padding: 0.75em;
    border-radius: 10px;
    font-family: "Outfit", sans-serif;
    font-size: var(--fs-400);

    border: 1px solid black;
  }

  textarea {
    resize: none;
    overflow-x: hidden;
    overflow-y: auto;
  }

  label {
    display: flex;
    flex-direction: column;
    gap: 0.5em;
    width: 50%;
    margin: 0 auto;
  }

  label p {
    align-self: flex-start;
    white-space: nowrap;
    padding-left: 0.5em;
  }

  button {
    width: 30%;
    margin: 0 auto;
    padding: 1em;
    background-color: #5539cd;
    font-family: "Outfit", sans-serif;
    font-size: var(--fs-300);
    color: var(--clr-neutral-50);
    border-radius: 100px;
    margin-top: 1em;
  }

  button:hover {
    background-image: linear-gradient(rgb(0 0 0/15%) 0 0);
    cursor: pointer;
  }

  #privacy {
    color: inherit;
  }

  @media screen and (max-width: 40em) {
    section {
      padding: 0.5em;
    }
    #features {
      flex-direction: column;
      gap: 2em;
    }

    .feature {
      width: auto;
    }

    form {
      width: 100%;
    }

    label {
      width: 100%;
    }
    button {
      width: 70%;
    }
  }
</style>
