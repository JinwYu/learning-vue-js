<template>
    <div>
    	<div id="container">
			<!-- Footer -->
			<footer>
			    <!-- Footer Links -->
			    <div class="container-fluid text-md-left">

					<!-- Grid row -->
					<div class="row">

				        <hr class="clearfix w-100 d-md-none pb-3">

				        <!-- Grid column -->
				        <div class="col-md-2 mb-md-0 mb-3">
				            <!-- Links -->
				            <h5 class="text-uppercase">INFORMATION</h5>

				            <ul class="list-unstyled">
								<li><a href="#!">About Us</a></li>
								<li><a href="#!">Work With US</a></li>
								<li><a href="#!">Privacy Policy</a></li>
								<li><a href="#!">Terms & Conditions</a></li>
								<li><a href="#!">Press Engquiries</a></li>
				            </ul>
			        	</div>

				        <!-- Grid column -->
				        <div class="col-md-4 mb-md-0 mb-3">
				            <!-- Links -->
				            <h5 class="text-uppercase">CUSTOMER SERVICE</h5>

				            <ul class="list-unstyled">
								<li><a href="#!">Contact Us</a></li>
								<li><a href="#!">Ordering & Payment</a></li>
								<li><a href="#!">Shipping</a></li>
								<li><a href="#!">Returns</a></li>
								<li><a href="#!">FAQ</a></li>
				            </ul>
				        </div>

				        <!-- Grid column -->
				        <div class="col-md-6 mt-md-0 mt-3">
				            <div id="about">
								<!-- Content -->
								<h5 class="text-uppercase">Footer Content</h5>
								<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut.</p>
				          </div>
				        </div>

			    	</div>

			    </div>

			</footer>
		</div>
    </div>
</template>

<style scoped>

/* Ugly quick fix to get rid of overlapping text when at around 1024px horizontally */
/* Should be fixed with divs that stack instead but too late to fix now. */
/* Maybe trigger the stacking which is already implemented at an earlier resolution */
.col-md-2{
	overflow: hidden;
}

#container{
  	background: #2699FB;
}

footer {
	color: white;
	padding-top: 3%;
	padding-bottom: 3%;
}

a {
	font-size: 15px;
	color: white;
}

.row{
	max-width: 80%;
  	margin: auto;

  	padding-left: 2em;
  	padding-right: 1em;
}

#about{
	float: right;
	font-size: 15px;
}

.text-uppercase{
	font-size: 20px;
	padding-bottom: 10px;
}

@media screen and (max-width: 1024px) {
    .row{
		max-width: 100%;

		padding-left: 0em;
  		padding-right: 0em;
	}
}


</style>