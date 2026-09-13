<script lang="ts">
	import barefootStoreImage from '$lib/assets/images/barefoot-store.png';
	import SplitHero from '$lib/components/SplitHero.svelte';
	import { m } from '$lib/paraglide/messages.js';
</script>

<SplitHero
	title={m.home_database_barefoot()}
	description={m.database_project_barefoot_store_description()}
	image={barefootStoreImage}
	imageAlt={m.home_database_barefoot_image_alt()}
/>
