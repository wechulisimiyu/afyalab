<section class="hero d-flex justify-content-center align-items-center" id="section_1">
	<div class="container">
		<div class="row">
			<div class="col-lg-7 col-12">
				<div class="hero-text">
					<div class="hero-title-wrap d-flex align-items-center mb-4">
						<h1 class="hero-title ms-3 mb-0 mt-5">Who we are</h1>
					</div>

					<p style="color: #ffffff;">
						An innovation space, set to transform the healthcare technology sector in Kenya and
						beyond.
					</p>
				</div>
			</div>
		</div>
	</div>

	<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"
		><path
			fill="#1b263b"
			fill-opacity="1"
			d="M0,160L24,160C48,160,96,160,144,138.7C192,117,240,75,288,64C336,53,384,75,432,106.7C480,139,528,181,576,208C624,235,672,245,720,240C768,235,816,213,864,186.7C912,160,960,128,1008,133.3C1056,139,1104,181,1152,202.7C1200,224,1248,224,1296,197.3C1344,171,1392,117,1416,90.7L1440,64L1440,0L1416,0C1392,0,1344,0,1296,0C1248,0,1200,0,1152,0C1104,0,1056,0,1008,0C960,0,912,0,864,0C816,0,768,0,720,0C672,0,624,0,576,0C528,0,480,0,432,0C384,0,336,0,288,0C240,0,192,0,144,0C96,0,48,0,24,0L0,0Z"
		/></svg
	>
</section>

<style>
	.hero {
		background: var(--secondary-color);
		position: relative;
		overflow: hidden;
		padding-top: 330px;
		padding-bottom: 330px;
	}

	@media screen and (min-width: 991px) {
		.hero {
			height: 60vh;
		}
	}

	.hero-title,
	.hero h2 {
		background: var(--white-color);
		box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175);
		border-radius: var(--border-radius-large);
		display: inline-block;
		padding: 8px 24px;
	}

	.hero-title {
		font-size: 44px;
	}

	.hero h2 {
		font-size: 38px;
	}

	.hero-text {
		position: relative;
		z-index: 22;
		top: 70px;
	}

	.hero-image-wrap {
		background: var(--white-color);
		border-radius: 100%;
		width: 350px;
		height: 350px;
		position: absolute;
		z-index: 22;
		top: -50px;
		right: 0;
		left: 0;
		margin: auto;
		pointer-events: none;
	}

	.hero-image {
		position: absolute;
		z-index: 22;
		top: 0;
		width: 100%;
		min-width: 550px;
	}

	.hero svg {
		position: absolute;
		z-index: 2;
		bottom: 0;
		right: 0;
		left: 0;
		overflow: hidden;
		height: 100%;
		pointer-events: none;
	}
</style>
