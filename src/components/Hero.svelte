<script>
    import "../styles/global.css";
</script>

<div id="hero">
    <div id="hero-left">
        <p id="tag">Reach new horizons.</p>
        <p id="expand">We build and maintain high performance websites for small businesses, at an affordable monthly cost.</p>
        <button href="/contact">let's get started! <img src="send-dark.svg" alt=" "></button>
    </div>
        <img class="wave" src="wave.svg" alt=" ">
</div>

<style>
    #hero {
		position: relative;
		background-image: url('hero.webp');
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

	#tag {
		color: white;
		mix-blend-mode: screen;
		font-family: 'Outfit', sans-serif;
		font-size: 72px;
		font-weight: 900;
	}

	#expand {
		font-family: 'Outfit', sans-serif;
		font-weight: 400;
		color: #F7F5F3;
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
		font-family: 'Outfit', sans-serif;
		color: #27294A;
		font-weight: 400;
		font-size: 24px;
		white-space: nowrap;

		background-color: #F3E9AC;

		border: 2px solid #F3E9AC;
		border-radius: 50px;
	}

    button:hover {
        background-color: #EEC447;
        border: 2px solid #EA8827;
    }

	.wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.wave svg {
    position: relative;
    display: block;
    width: calc(171% + 1.3px);
    height: 90px;
}



</style>