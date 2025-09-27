<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons (none currently needed)
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Developer first",
			description: "Every decision we make starts with how it affects the developer experience. No boilerplate, no friction, just flow."
		},
		{
			title: "Unified simplicity",
			description: "We believe complex integrations shouldn't require complex solutions. One interface, infinite possibilities."
		},
		{
			title: "API transparency", 
			description: "Your APIs should work together seamlessly. We make the invisible visible and the complex simple."
		},
		{
			title: "Build fast, ship faster",
			description: "Time spent wrestling with API integrations is time stolen from building great products. We give you that time back."
		}
	];
</script>

<SecondaryHero
	title="One interface to rule APIs"
	subtitle="Goodbye boilerplate. Hello flow."
	imageSrc="/generated/image-a-candid-documentary-style-photo-of-a-di.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Every developer knows the frustration: you need to integrate five different APIs, and each one has its own authentication, rate limits, error handling, and documentation style. What should take hours stretches into weeks.",
		"We built Fous because we lived this pain ourselves. After spending more time wrestling with API integrations than actually building features, we realized the internet needed a new way to connect services.",
		"The solution wasn't another API marketplace or documentation tool. It was a unified interface that makes every API feel like it was built by the same team, with consistent patterns and predictable behavior.",
		"Today, developers use Fous to focus on what matters: building products that users love. Because time spent on boilerplate is time stolen from innovation."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed - no information available for Fous -->

<!-- CTA Section -->
<CallToAction
	title="Ready to unify your APIs?"
	subtitle="Stop wrestling with integrations"
	description="Join the developers who've already discovered how much faster they can build when all their APIs work together through one powerful interface."
	imageSrc="/generated/image-a-clean-minimalist-office-space-where-a-.webp"
/>
