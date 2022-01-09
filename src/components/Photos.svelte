<script>
	import GalleryImage from './GalleryImage.svelte';
</script>

<style>
</style>

<div class="photos p-4 md:flex md:items-center md:p-20">
	<div class="w-full grid grid-cols-2	gap-2 xl:flex xl:items-center xl:gap-3">
		<GalleryImage src="salon-curly.webp" alt="Curly Hair" />
		<GalleryImage src="salon-love.webp" alt="Straight Hair" />
		<GalleryImage src="salon-washing.webp" alt="Hair Salon Hair Washing Area" />
		<GalleryImage src="salon-whole.webp" alt="Salon" />
	</div>
</div>
