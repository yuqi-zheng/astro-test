<script>
    import "../styles/global.css";
</script>

<div id="hero">
    <div id="hero-left">
        <p id="tag">Reach new horizons.</p>
        <p id="expand">We build and maintain high performance websites for small businesses, at an affordable cost.</p>
        <button>let's get started! <img src="send-dark.svg" alt=" "></button>
    </div>
    <div class="wave">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
        </svg>
    </div>
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
		position: absolute;
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
		
		font-family: 'Outfit', sans-serif;
		color: #27294A;
		font-weight: 400;
		font-size: 24px;
		white-space: nowrap;
		


		background: #F3E9AC;

		border: 2px solid #F3E9AC;
		border-radius: 50px;
	}

	.wave {
		position: absolute;
		bottom: 0;
		left: 0;
		width: 100%;
		overflow: hidden;
		line-height: 0;
		transform: rotate(180deg);
	}

    .wave svg {
        position: relative;
        display: block;
        width: calc(150% + 1.3px);
        height: 180px;
    }

    .wave .shape-fill {
        fill: #F7F5F3;
    }

</style>