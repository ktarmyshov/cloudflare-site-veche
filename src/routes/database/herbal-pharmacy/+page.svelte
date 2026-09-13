<script lang="ts">
	import herbalPharmacyImage from '$lib/assets/images/herbal-pharmacy.png';
	import SplitHero from '$lib/components/SplitHero.svelte';
	import { m } from '$lib/paraglide/messages.js';
</script>

<SplitHero
	title={m.home_database_herbal_pharmacy()}
	description={m.database_project_herbal_pharmacy_description()}
	image={herbalPharmacyImage}
	imageAlt={m.home_database_herbal_pharmacy_image_alt()}
/>
