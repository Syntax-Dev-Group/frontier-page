<script>
	import logo from '../lib/assets/favicon.png';
	import outgoing from '../lib/assets/outgoing.svg'
</script>

<nav>
	<div class="logo"><img class="logo-img" src={logo} alt="Syntax Dev Logo" /></div>
	<!-- <img class="about-img"src={about} alt="building about logo"> -->
	<div class="about"><a href="/about">ABOUT</a></div>
	<div class="showcase"><a href="/pricing">PRICING</a></div>
	<div class="contact"><a href="/contact">CONTACT</a></div>
</nav>
<main>
	<section class="intro-text">
		<div class="main-text-container">
			We make
			<span class="special-text-v1" data-text="discord">&nbsp;discord</span>
			<br/>
			<span class="bots-text">Bots</span>
			<br/>
			<br/>
			<a class="btn-pricing" href="/pricing"><span>Pricing</span><img class="outgoing-img" src={outgoing} alt="out going"></a>
		</div>
	</section>
</main>

<style>
	nav {
		display: flex;
		flex-direction: row;
		text-align: center;
		align-items: center;
		flex-basis: 100px;
		background: rgb(0, 0, 0);
		border-bottom: 2px solid gray;
	}
	main {
		background-image: linear-gradient(to bottom, black, rgb(19, 19, 19));
	}

	nav > div {
		font-size: 16px;
		transition: background 0.3s;
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	nav > .about:hover,
	.contact:hover,
	.showcase:hover {
		background: rgb(27, 27, 27);
		cursor: pointer;
	}

	nav > .about:active,
	.contact:active,
	.showcase:active {
		background: rgb(54, 54, 54);
	}

	@media only screen and (max-width: 600px) {
		nav > .about:active,
		.contact:active,
		.showcase {
			display: none;
		}
	}

	nav > .logo {
		justify-content: start;
	}

	nav > div > a {
		color: white;
		text-decoration: none;
	}

	.logo {
		flex-grow: 2;
		text-align: left;
	}
	.logo-img {
		height: 100px;
		width: 100px;
	}
	.about {
		flex-grow: 1;
	}
	/* 
    .about-img {
        margin-left: 5px;
        vertical-align: middle;
        height: 16px
    } */

	.showcase {
		flex-grow: 1;
	}
	.contact {
		flex-grow: 1;
	}
	main {
		flex-grow: 1;
	}

	.intro-text {
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	

	.intro-text {
		font-weight: 700;
		font-size: 70px;
	}

	.special-text-v1 {
		padding-left: 10px;
		position: relative;
		color: transparent;
		-webkit-text-stroke: 1px #5865f2;
		text-transform: uppercase;
	}

	.special-text-v1::before {
		content: attr(data-text);
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		color: #5865f2;
		-webkit-text-stroke: 0px #5865f2;
		border-right: 2px solid #5865f2;
		overflow: hidden;
		animation: animate 6s linear infinite;
	}

	@keyframes animate {
		0%,
		10%,
		100% {
			width: 0;
		}

		70%,
		90% {
			width: 100%;
		}
	}

	.bots-text {
		background: url('../lib/assets/jGIGWOA.jpg');
		background-clip: text;
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
	}

	.btn-pricing {
		display: flex;
		align-items: center;
		margin: 0;
		background-color: #5865f2;
		border-radius: 50px;
		padding: 20px 50px;
		color: white;
		border: none;
		font-size: 40px;
		transition: background 0.3s;
		text-decoration: none;
		width: 176px
	}

	.btn-pricing:hover {
		background-color: #7681f3;
		color: rgb(238, 232, 232);
		cursor: pointer;
	}

	.outgoing-img {
		align-items: end;
		width: 50px;
		transition: fill 0.3s
	}

</style>
