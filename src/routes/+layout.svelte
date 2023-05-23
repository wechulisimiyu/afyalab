<script>
	import Header from './Header.svelte';
	import Preloader from './Preloader.svelte';
	import './home.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<footer class="site-footer">
		<div class="container">
			<div class="row">
				<div class="col-lg-12 col-12">
					<div class="copyright-text-wrap">
						<p class="mb-0">
							<span class="copyright-text">Copyright © 2023 Afya Innovation Hub</span>
						</p>
					</div>
				</div>
			</div>
		</div>
	</footer>
	<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
	<script
		src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
		integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
		crossorigin="anonymous"
	></script>
	<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</div>
