<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Stop building API connectors. Start building features."
	subtitle="Fous transforms scattered API integrations into unified workflows through a single powerful interface. Spend less time on boilerplate, more time on what matters."
	imageSrc="/generated/image-a-candid-documentary-style-photograph-of.webp"
	callsToAction={[
		{ href: "#demo", label: "Try demo" },
		{ href: "#docs", label: "View docs" }
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/discord.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Arjun Patel",
			position: "Senior Full-Stack Developer",
			company: "StreamFlow Analytics",
			quote:
				"Before Fous, I was spending 3 weeks building custom connectors for every new API integration. Now I can connect any service in minutes. We've reduced our integration timeline from weeks to hours - that's saved us over $50K in development costs this quarter alone.",
			image: "/generated/image-candid-environmental-portrait-of-a-confi.webp"
		},
		{
			name: "Keisha Williams",
			position: "Engineering Lead",
			company: "Velocity Labs",
			quote:
				"Our startup needed to integrate 15 different APIs for our MVP. Fous eliminated the risk of integration failures that could have delayed our launch by months. Instead of managing 15 different authentication systems and rate limits, we have one unified interface. Game changer.",
			image: "/generated/image-documentary-style-headshot-of-a-confiden.webp"
		},
		{
			name: "Carlos Rodriguez",
			position: "Technical Co-founder",
			company: "DataSync Pro",
			quote:
				"We were burning through our runway building API wrappers instead of our core product. Fous gave us back 40 hours per week that we now spend on features customers actually want. The unified error handling alone has prevented countless production issues.",
			image: "/generated/image-authentic-candid-headshot-of-a-confident.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
