---
layout: default
---

	<body>

		<div class="container">

			<section>
				<div class="tabs tabs-style-topline">
					<nav>
						<h3>Week 7</h3>
						<ul>
							<li>
								<a href="#section-topline-1" class="icon"><img src="img/concept.svg" alt=""><span>Concepts</span></a></li>
							<li>
								<a href="#section-topline-2" class="icon"><img src="img/practice.svg" alt=""><span>Practice</span></a></li>
							<li>
								<a href="#section-topline-3" class="icon">
								<img src="img/application.svg" alt=""><span>Applications</span></a></li>
						</ul>
					</nav>
					<div class="content-wrap">
						<section id="section-topline-1">
							

							<p>Check In: Grid Based Layout</p>
							<ol>
								<li><a href="https://github.com/vcd/website-starter">Download 368 Starter</a></li>
								<li>Create 1-3-1 column layout. Refer to `grid.css`</li>
								<li>Add you own content</li>
							</ol>
							
							<p>Advanced Selectors</p>
							<p>Refer to <a href="http://teamtreehouse.com/library/css-selectors">TH: CSS Selectors</a></p>

						</section>
						<section id="section-topline-2">
							
							<p>Practice Using</p>	
							<ul>
								<li>Child, Adjacent, and General Sibling Combinators</li>
								<li>Attribute with substring matching</li>
								<li>First & Last Child</li>
								<li>Psuedo Classes</li>
								<li>:nth-child</li>
								<li>Psuedo Elements</li>
							</ul>

						</section>
						<section id="section-topline-3">

								<p>TBA</p>
						</section>
					</div><!-- /content -->
				</div><!-- /tabs -->
			</section>

		</div><!-- /container -->

		<script src="js/cbpFWTabs.js"></script>
		<script>
			(function() {

				[].slice.call( document.querySelectorAll( '.tabs' ) ).forEach( function( el ) {
					new CBPFWTabs( el );
				});

			})();
		</script>
	</body>
</html>
