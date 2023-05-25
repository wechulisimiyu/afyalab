<section class="contact section-padding" id="contact">
	<div class="container">
		<div class="row">
			<div class="col-lg-6 col-md-8 col-12">
				<div class="section-title-wrap d-flex justify-content-start align-items-center mb-5">
					<h2 class="text-white ms-4 mb-0">Reach Out</h2>
				</div>
			</div>

			<div class="clearfix" />

			<div class="col-lg-3 col-md-6 col-12 pe-lg-0">
				<div class="contact-info contact-info-border-start d-flex flex-column">
					<strong class="site-footer-title d-block mb-3">Services</strong>

					<ul class="footer-menu">
						<li class="footer-menu-item"><a href="" class="footer-menu-link">Ideation</a></li>

						<li class="footer-menu-item"><a href="" class="footer-menu-link">Funding</a></li>

						<li class="footer-menu-item"><a href="" class="footer-menu-link">Partnership</a></li>

						<li class="footer-menu-item"><a href="" class="footer-menu-link">Research</a></li>
					</ul>

					<strong class="site-footer-title d-block mt-4 mb-3">Socials</strong>

					<ul class="social-icon">
						<li class="social-icon-item"><a href="#" class="social-icon-link bi-twitter" /></li>

						<li class="social-icon-item"><a href="#" class="social-icon-link bi-instagram" /></li>
					</ul>

					<strong class="site-footer-title d-block mt-4 mb-3">Start a project</strong>

					<p class="mb-0">Find out our activities</p>
				</div>
			</div>

			<div class="col-lg-3 col-md-6 col-12 ps-lg-0">
				<div class="contact-info d-flex flex-column">
					<strong class="site-footer-title d-block mb-3">About</strong>

					<p class="mb-2">Igniting Medical Innovation.</p>

					<strong class="site-footer-title d-block mt-4 mb-3">Email</strong>

					<p>
						<a href="mailto:afyainnovationlab@gmail.com"> afyainnovationlab@gmail.com </a>
					</p>

					<!-- <strong class="site-footer-title d-block mt-4 mb-3">Call</strong>

                            <p class="mb-0">
                                <a href="tel: 120-240-9600">
                                    120-240-9600
                                </a>
                            </p> -->
				</div>
			</div>

			<div class="col-lg-6 col-12 mt-5 mt-lg-0">
				<form action="#" method="get" class="custom-form contact-form">
					<div class="row">
						<div class="col-lg-6 col-md-6 col-12">
							<div class="form-floating">
								<input
									type="text"
									name="name"
									id="name"
									class="form-control"
									placeholder="Name"
									required=""
								/>

								<label for="floatingInput">Name</label>
							</div>
						</div>

						<div class="col-lg-6 col-md-6 col-12">
							<div class="form-floating">
								<input
									type="email"
									name="email"
									id="email"
									pattern="[^ @]*@[^ @]*"
									class="form-control"
									placeholder="Email address"
									required=""
								/>

								<label for="floatingInput">Email address</label>
							</div>
						</div>

						<div class="col-lg-3 col-md-6 col-6">
							<div class="form-check form-check-inline">
								<input
									name="ideation"
									type="checkbox"
									class="form-check-input"
									id="inlineCheckbox1"
									value="1"
								/>

								<label class="form-check-label" for="inlineCheckbox1">
									<i class="bi-lightbulb form-check-icon" />
									<span class="form-check-label-text">Ideation</span>
								</label>
							</div>
						</div>

						<div class="col-lg-3 col-md-6 col-6">
							<div class="form-check form-check-inline">
								<input
									name="funding"
									type="checkbox"
									class="form-check-input"
									id="inlineCheckbox2"
									value="1"
								/>

								<label class="form-check-label" for="inlineCheckbox2">
									<i class="bi-wallet form-check-icon" />
									<span class="form-check-label-text">Funding</span>
								</label>
							</div>
						</div>

						<div class="col-lg-3 col-md-6 col-6">
							<div class="form-check form-check-inline">
								<input
									name="partnership"
									type="checkbox"
									class="form-check-input"
									id="inlineCheckbox3"
									value="1"
								/>

								<label class="form-check-label" for="inlineCheckbox3">
									<i class="bi-info-square form-check-icon" />
									<span class="form-check-label-text">Partnership</span>
								</label>
							</div>
						</div>

						<div class="col-lg-3 col-md-6 col-6">
							<div class="form-check form-check-inline me-0">
								<input
									name="research"
									type="checkbox"
									class="form-check-input"
									id="inlineCheckbox4"
									value="1"
								/>

								<label class="form-check-label" for="inlineCheckbox4">
									<i class="bi-search form-check-icon" />
									<span class="form-check-label-text">Research</span>
								</label>
							</div>
						</div>

						<div class="col-lg-12 col-12">
							<div class="form-floating">
								<textarea
									class="form-control"
									id="message"
									name="message"
									placeholder="Talk to us"
								/>

								<label for="floatingTextarea">Talk to us</label>
							</div>
						</div>

						<div class="col-lg-3 col-12 ms-auto">
							<button type="submit" class="form-control">Send</button>
						</div>
					</div>
				</form>
			</div>
		</div>
	</div>
</section>

<style>
	.contact {
		background: var(--section-bg-color);
	}

	.contact-info {
		background: var(--white-color);
		border-top-right-radius: var(--border-radius-small);
		border-bottom-right-radius: var(--border-radius-small);
		padding: 60px 30px 30px 30px;
		height: 100%;
	}

	.contact-info-border-start {
		border-right: 1px solid var(--border-color);
		border-radius: var(--border-radius-small) 0 0 var(--border-radius-small);
	}

	.contact-form {
		margin-left: 10px;
	}

	.custom-form .form-control {
		background: var(--white-color);
		box-shadow: none;
		border: 2px solid var(--border-color);
		color: var(--p-color);
		margin-bottom: 24px;
		padding-top: 13px;
		padding-bottom: 13px;
		outline: none;
	}

	.form-floating > label {
		color: var(--p-color);
	}

	.form-check-inline {
		vertical-align: middle;
		width: 100%;
		position: relative;
		margin-right: 0;
		margin-top: 0;
		margin-bottom: 24px;
		padding: 0;
	}

	.custom-form .form-check-label {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		text-align: center;
	}

	.form-check-label-text {
		color: var(--p-color);
		display: block;
		font-size: copyright-font-size;
		margin-top: 5px;
	}

	.form-check-input[type='checkbox'] {
		background: var(--white-color);
		border: 2px solid var(--border-color);
		box-shadow: none;
		outline: none;
		width: 100%;
		margin-top: 0;
		margin-left: 0;
		padding: 40px 50px;
	}

	.form-check-input:checked[type='checkbox'] {
		background-image: none;
	}

	.form-check-input:hover,
	.form-check-input:checked {
		background-color: transparent;
		border-color: var(--secondary-color);
	}

	.custom-form .form-control:hover,
	.custom-form .form-control:focus {
		background: transparent;
		border-color: var(--secondary-color);
	}

	.custom-form .form-floating textarea {
		height: 150px;
	}

	.custom-form button[type='submit'] {
		background: var(--secondary-color);
		border: none;
		border-radius: var(--border-radius-large);
		color: var(--white-color);
		font-weight: var(--font-weight-bold);
		transition: all 0.3s;
		margin-bottom: 0;
	}

	.custom-form button[type='submit']:hover,
	.custom-form button[type='submit']:focus {
		background: var(--primary-color);
		border-color: transparent;
	}
</style>
