<script lang="ts">
	import rabiaImage from '$lib/assets/images/rabia.png';
	import SplitHero from '$lib/components/SplitHero.svelte';
	import { m } from '$lib/paraglide/messages.js';
</script>

<SplitHero
	title={m.home_database_rabia()}
	description={m.database_project_rabia_description()}
	image={rabiaImage}
	imageAlt={m.home_database_rabia_image_alt()}
/>
