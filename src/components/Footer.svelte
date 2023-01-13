<script>
</script>

<div id="container">
  <div id="waves">
    <img class="wave-top" src="footer-wave-top.svg" alt=" " />
    <img class="wave-bottom" src="footer-wave-bottom.svg" alt=" " />
  </div>
  <footer>
    <div id="rows">
      <div id="row-1">
        <ul id="coa-text">
          <li id="how-can-we-help">How can we help?</li>
          <li>Contact us at anytime!</li>
        </ul>
        <div id="coa">
          <p id="send-us-a-message">send us a message</p>
          <p id="coa-email">hello@lambda-digital.com.au</p>
        </div>
      </div>

      <div id="row-2">
        <div id="about">
          <img id="logo" src="logo-long.svg" alt="" />
          <p>
            Lambda Digital is a digital media team based in Melbourne,
            specialising in high performance websites for small businesses. We
            provide a full package service with ongoing maintenance, at an
            affordable monthly cost.
          </p>
          <a href="/about"><u>Learn more</u></a>
        </div>
        <div id="nav">
          <h3>Navigation</h3>
          <ul id="nav-list">
            <li><a href="/services">Services</a></li>
            <li><a href="/about">About Us</a></li>
          </ul>
        </div>
        <div id="contact">
          <h3>Contact</h3>
          <ul id="contact-list">
            <li>hello@lambda-digital.com.au</li>
            <li>64 Zoo Lane</li>
          </ul>
        </div>
        <div id="social">
          <img src="facebook.svg" alt="Facebook" />
          <img class="social-icon" src="linkedin.svg" alt="Linked In" />
          <img src="instagram.svg" alt="Instagram" />
        </div>
      </div>
    </div>
  </footer>
</div>

<style>
  #container {
    display: flex;
    flex-direction: column;
    margin-top: 15vh;
  }

  #waves {
    background-color: #f7f5f3;
    position: relative;
  }
  footer {
    position: relative;
    bottom: 0;
    background-color: #383971;
    padding: 4em 3em 2em 3em;
    font-family: "Outfit", sans-serif;
    color: #f7f5f3;
    z-index: 6;
  }

  #rows {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 6em;
  }

  #row-1 {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  #coa-text {
    font-size: 3em;
    font-weight: var(--fw-bold);
    list-style: none;
  }

  #how-can-we-help {
    color: #f3e9ac;
  }

  #coa {
    width: 22em;
    height: 4.5em;
    border-radius: 1.5em;
    background-color: #f7f5f3;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 2em;
    font-size: 1.25em;
  }

  #send-us-a-message {
    color: #86949f;
    white-space: nowrap;
  }

  #coa-email {
    color: #303438;
    white-space: nowrap;
    font-weight: var(--fw-bold);
  }

  #row-2 {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  h3 {
    font-weight: var(--fw-bold);
  }

  #logo {
    min-width: 12.5em;
    max-width: 12.5em;
  }

  #about {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    gap: 2em;
    width: 40%;
    transform: translateY(-1em);
  }

  #about a {
    color: #f7f5f3;
  }

  #nav {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    gap: 2em;
  }

  #nav-list {
    list-style: none;
    font-weight: var(--fw-bold);
  }

  #nav-list a {
    text-decoration: none;
    color: #f3e9ac;
  }

  #nav-list a:hover {
    text-decoration: underline;
  }

  #contact {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    text-align: center;
    gap: 2em;
  }

  #contact-list {
    display: flex;
    flex-direction: column;
    gap: 1.5em;
    list-style: none;
  }

  #social {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 1.75em;
  }

  .social-icon {
    max-width: 2em;
  }
  .wave-top {
    position: absolute;
    bottom: -0.5em;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 5;
  }

  .wave-bottom {
    position: absolute;
    bottom: -5em;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 4;
  }
</style>
