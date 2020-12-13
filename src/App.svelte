<script>
	// Import components
	import Nav from "./components/Nav.svelte";
	import Footer from "./components/Footer.svelte";
</script>

<style>
	.fleximagetext {
		display: flex;
		flex-direction: row;
		padding: 10px 0;
	}

	.text-container {
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.imgHeading {
		margin-right: 10px;
		border-radius: var(--borderRadius);
	}

	.imgBig {
		margin-right: 10px;
		border-radius: var(--borderRadius);
	}

	.imgSupport {
		max-width: 320px;
		margin-left: 20px;
		border-radius: var(--borderRadius);
	}
</style>

<main>
	<!-- Nav bar component -->
	<Nav />

	<!-- Hamburger menu items -->
	<div id="myLinks">
		<a href="#home">Home</a>
		<a href="#services">Services</a>
		<a href="#forms">Client Forms</a>
		<a href="#insurance">Insurance</a>
		<a href="#about">About</a>
		<a href="#contact">Contact</a>
	</div>

	<!-- Main logo with image at top of page -->
	<div id="home" class="carousel ">
		<!-- <div class="logo">
			<img
				class="responsiveImage"
				src="images/logo_center.png"
				alt="Masullo Counseling Logo" />
		</div> -->
	</div>

	<!-- Services Card -->
	<div id="services" class="card">
		<div class="fleximagetext">
			<img class="imgHeading" src="/images/hands.png" alt="Hands" />
			<div class="text-container">
				<h3>Services Offered</h3>
			</div>
		</div>

		<p>
			Masullo Counseling provides comprehensive counseling services for
			Individuals, Couples, and Families
		</p>

		<div class="fleximagetext">
			<div class="text-container">
				<strong>Specializing in:</strong>
				<ul>
					<li>PTSD</li>
					<li><a target="_blank" href="https://www.emdria.org/">EMDR</a></li>
					<li>
						<a target="_blank" href="https://www.iceeft.com/">Emotionally
							Focused Couples Counseling</a>
					</li>
					<li>Depression and Anxiety</li>
					<li>Parenting Support</li>
					<li>Grief Counseling</li>
					<li>Stress Management</li>
				</ul>
			</div>

			<img class="imgSupport" src="/images/support.jpg" alt="Support" />
		</div>

		<p>
			Please call or email today for an appointment.
			<a href="#contact">Contact Me</a>
		</p>
	</div>

	<!-- Client Forms Card -->
	<div id="forms" class="card">
		<div class="fleximagetext">
			<img class="imgHeading" src="/images/forms.png" alt="Forms" />
			<div class="text-container">
				<h3>Client Forms</h3>
			</div>
		</div>

		<p>
			Please download these forms, fill them out, and fax or email back prior to
			your first vist, thank you!
		</p>
		<ul>
			<li>
				<a
					target="_blank"
					href="https://res.cloudinary.com/masullodevcloud/image/upload/v1607776397/masullo_counseling/2017_Informed_Consent_Agreement_gefizo.pdf">Informed
					Consent Agreement</a>
			</li>
			<li>
				<a
					target="_blank"
					href="https://res.cloudinary.com/masullodevcloud/image/upload/v1607776405/masullo_counseling/Patient_info_he4wlp.pdf">Patient
					Information Form</a>
			</li>
		</ul>
		<p><a href="#contact">Contact Me</a></p>
	</div>

	<!-- Insurance Card -->
	<div id="insurance" class="card">
		<div class="fleximagetext">
			<img class="imgHeading" src="/images/insurance.png" alt="Insurance" />
			<div class="text-container">
				<h3>Insurance Accepted</h3>
			</div>
		</div>

		<p>
			Currently I accept only Tricare insurance.
			<br />
			Please check with your insurance company and verify your mental health
			coverage.
			<br />
			If you do not have Tricare Insurance, you may pay with cash, personal
			check, or credit card for your care.
		</p>
		<img class="imgBig" src="/images/CC.jpg" alt="Credit Accepted" />
		<p>
			If you are active duty military and do not wish to utilize your Tricare
			benefits or go through your primary care provider for a referral,
			counseling services are available on a fee for service basis. This assures
			complete confidentiality.
		</p>
		<p>Please <a href="#contact">contact me</a> for information.</p>
	</div>

	<!-- About Card -->
	<div id="about" class="card">
		<div class="fleximagetext">
			<img class="imgHeading" src="/images/about.jpg" alt="About" />
			<div class="text-container">
				<h3>About Masullo Counseling</h3>
			</div>
		</div>

		<div class="fleximagetext">
			<img class="imgBig" src="/images/Diane.jpg" alt="Diane Masullo" />
			<div class="text-container">
				<p><strong>Diane E. Masullo, MS, LPC, LMFT</strong></p>
				<p>
					Diane spent ?? years as RN in varied specialties, Oncology/Aids,
					Medical/Surgical, Pediatrics, and Emergency Medicine.
					<br />
					She took that experience and pursued a Masters in Psychology. Her
					passion is serving soldiers and their families.
					<br />
					She specializes in therapy for the individual and entire family.
				</p>
				<p>
					Diane has been working with soldiers and their families for many years
					and will continue to serve this deserving population.
				</p>
			</div>
		</div>
	</div>

	<!-- Contact Card -->
	<div id="contact" class="card">
		<div class="fleximagetext">
			<img class="imgHeading" src="/images/contact.jpg" alt="Contact" />
			<div class="text-container">
				<h3>Contact Information</h3>
			</div>
		</div>

		<p>
			Need an appointment or information, please call or email.
			<br />
			<a target="_blank" href="mailto:diane@masullocounseling.com">
				Click to Email
			</a>
		</p>

		<p>
			<strong>Masullo Counseling Center</strong>
			<br />
			1003 West Highway 190
			<br />
			Copperas Cove, TX 76522
			<br />
			Office: (254) 547-3040
			<br />
			Fax: (800) 516-3152
		</p>
		<!-- Google Map to Masullo Counseling -->
		<iframe
			src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3416.2187866460627!2d-97.92397088405131!3d31.103650574710592!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x865ab72eb7a0fa17%3A0x4aac3eaf7dd54360!2sMasullo%20Counseling%20Center!5e0!3m2!1sen!2sus!4v1607713484552!5m2!1sen!2sus"
			width="600"
			height="450"
			frameborder="0"
			style="border:0;"
			allowfullscreen=""
			aria-hidden="false"
			tabindex="0"
			title="Map to Masullo Counseling" />
	</div>

	<!-- Footer component -->
	<Footer />
</main>
