<script>

</script>

<footer>
    <div class="wave-top">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M985.66,92.83C906.67,72,823.78,31,743.84,14.19c-82.26-17.34-168.06-16.33-250.45.39-57.84,11.73-114,31.07-172,41.86A600.21,600.21,0,0,1,0,27.35V120H1200V95.8C1132.19,118.92,1055.71,111.31,985.66,92.83Z" class="shape-fill"></path>
        </svg>
    </div>

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
                <img id="logo" src="logo-long.svg" alt="">
                <p>Lambda Digital is a digital media team based in Melbourne, specialising in high performance websites for small businesses. 
                    We provide a full package service and ongoing maintenance, at an affordable monthly cost.</p>
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
                <img src="facebook.svg" alt="Facebook">
                <img class="social-icon" src="linkedin.svg" alt="Linked In">
                <img src="instagram.svg" alt="Instagram">
            </div>
        </div>
    </div>

</footer>

<style>
    footer {
        position: relative;
        bottom: 0;
        background-color: #383971;
        padding: 150px 48px 32px 48px;
        font-family: 'Outfit', sans-serif;
        color: #F7F5F3;
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
        color: #F3E9AC;
    }

    #coa {
        box-sizing: border-box;
        width: 400px;
        height: 80px;
        border-radius: 25px;
        background-color: #F7F5F3;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 25px;
        font-size: 20px;
    }

    #send-us-a-message {
        color: #86949F;
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
        color: #F7F5F3;
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
        color: #F3E9AC;
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
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
    }

    .wave-top svg {
        position: relative;
        display: block;
        width: calc(100% + 1.3px);
        height: 81px;
    }

    .wave-top .shape-fill {
        fill: #F7F5F3;
    }


.wave-bottom {
    position: absolute;
    z-index: 9;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.wave-bottom svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 60px;
    transform: rotateY(180deg);
}

.wave-bottom .shape-fill {
    fill: #B69BFF;
}

</style>