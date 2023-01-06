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
            provide a full package service and ongoing maintenance, at an
            affordable monthly cost.
          </p>
          <a href="/about">Learn more</a>
        </div>
        <div id="nav">
          <h3>Navigation</h3>
          <ul id="nav-list">
            <li><a href="/services">Services</a></li>
            <li><a href="/gallery">Gallery</a></li>
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
    padding: 72px 48px 32px 48px;
    font-family: "Outfit", sans-serif;
    color: #f7f5f3;
    z-index: 6;
  }

  #rows {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 100px;
  }

  #row-1 {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 200px;
  }

  #coa-text {
    font-size: 48px;
    font-weight: 600;
    list-style: none;
  }

  #how-can-we-help {
    color: #f3e9ac;
  }

  #coa {
    box-sizing: border-box;
    width: 400px;
    height: 80px;
    border-radius: 25px;
    background-color: #f7f5f3;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 25px;
    font-size: 20px;
  }

  #send-us-a-message {
    color: #86949f;
    white-space: nowrap;
  }

  #coa-email {
    color: #303438;
    white-space: nowrap;
    font-weight: 600;
  }

  #row-2 {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  h3 {
    font-weight: 600;
  }

  #logo {
    min-width: 200px;
    max-width: 200px;
  }

  #about {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    gap: 30px;
    width: 40%;
    transform: translateY(-16px);
  }

  #about a {
    color: #f7f5f3;
  }

  #nav {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    gap: 30px;
  }

  #nav-list {
    list-style: none;
    font-weight: 600;
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
    gap: 30px;
  }

  #contact-list {
    display: flex;
    flex-direction: column;
    gap: 20px;
    list-style: none;
  }

  #social {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 25px;
  }

  .social-icon {
    max-width: 25px;
  }
  .wave-top {
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 5;
  }

  .wave-bottom {
    position: absolute;
    bottom: -60px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    z-index: 4;
  }
</style>
