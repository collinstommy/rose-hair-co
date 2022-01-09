<script>
	import AppointmentLink from './AppointmentLink.svelte';
</script>

<style>
	.gmap {
		min-height: 00px;
	}
</style>

<div
	class="px-5 py-8 w-full grid gap-10 mt-2 md:px-14 md:mt-12 md:grid-cols-3 md:max-w-screen-2xl md:gap-12"
>
	<div>
		<h2 class="mb-4">Location</h2>
		<div class="gmap">
			<iframe
				loading="lazy"
				title="Rose hair company location"
				width="100%"
				height="300"
				id="gmap"
				src="https://maps.google.com/maps?q=1429%20Colonial%20Blvd%20Suite%20102,%20Fort%20Myers,%20FL%2033907,%20United%20States&t=&z=15&ie=UTF8&iwloc=&output=embed"
				frameborder="0"
				scrolling="no"
				marginheight="0"
				marginwidth="0"
			/>
		</div>
	</div>
	<div class="md:mb-12">
		<h2 id="appointment" class="mb-4">Book an appointment</h2>
		<div class="mb-6 mt-4">
			<h3 class="mb-2">Hair</h3>
			<AppointmentLink phone="239 900 6980" name="Lauren" />
			<AppointmentLink phone="239 292 5182" name="Arri" />
			<AppointmentLink phone="239 240 0815" name="Nicole" />
		</div>
		<div>
			<h3 class="mb-2">Tattoo</h3>
			<AppointmentLink phone="786 532 5197" name="Kim" />
		</div>
	</div>
	<div class="address-hours">
		<div class="mb-7 md:mb-12">
			<h2 class="mb-4">Address</h2>
			<p>
				1429 Colonial Blvd Suite 102<br />
				Fort Myers, FL 33907 <br />
				United States
			</p>
		</div>
		<div class="mb-7 md:mb-12">
			<h2 class="mb-4">Opening Hours</h2>
			<p><span class="font-bold">Open: </span>Tuesday - Saturday</p>
			<p><span class="font-bold">Closed: </span>Sunday & Monday</p>
		</div>
	</div>
	<div />
</div>
