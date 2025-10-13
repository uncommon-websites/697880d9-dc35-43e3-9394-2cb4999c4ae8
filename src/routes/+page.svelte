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
	title="Scale your wisdom without trading hours for dollars"
	subtitle="Create an interactive digital replica trained on your expertise. Answer thousands of questions while you focus on what matters most."
	imageSrc="/generated/image-a-cozy-interior-scene-with-warm-ambient-.webp"
/>
<LogoScroller
	label="Trusted by creators and experts worldwide"
	logoUrls={[
		'https://cdn.brandfetch.io/youtube.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/substack.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linkedin.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/patreon.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Delphi creates interactive digital replicas trained on your existing content, voice, and expertise. We serve coaches, consultants, and creators with 10K+ followers who spend countless hours answering the same questions. Your Digital Mind handles repetitive inquiries while you focus on high-value work, multiplying your impact without multiplying your hours."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Leadership Coach",
			company: "Elevate Coaching",
			quote:
				"I was spending 18 hours every week answering the same questions from potential clients. My Digital Mind now handles those conversations while I focus on high-value sessions. I've scaled my reach to 3,000 people without hiring a team.",
			image: "/generated/image-professional-headshot-of-a-confident-sou.webp"
		},
		{
			name: "Marcus Williams",
			position: "Business Consultant",
			company: "Growth Strategy Partners",
			quote:
				"The time I spent on repetitive discovery calls was draining my energy and limiting my growth. Now my Digital Mind qualifies leads and answers foundational questions 24/7. I've reclaimed 15 hours per week and doubled my client capacity.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "Course Creator",
			company: "Creative Mastery Academy",
			quote:
				"My students needed support between sessions, but I couldn't afford to hire staff. My Digital Mind provides personalized guidance anytime, maintaining that personal connection at scale. Student satisfaction increased by 40% while my workload decreased.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		}
	]}
/>

<Features
	title="Your expertise, infinitely available"
	subtitle="Scale your wisdom without trading hours for dollars through conversational AI trained on your unique voice and knowledge"
	features={[
		{
			title: "Be everywhere at once",
			description:
				"Answer thousands of questions simultaneously across every time zone while you sleep, focusing your time on high-value interactions that truly need your personal attention."
		},
		{
			title: "Clone your voice and personality",
			description:
				"Train your Digital Mind on your content, voice, and expertise so every interaction feels authentically you, never generic AI."
		},
		{
			title: "Deploy across every channel",
			description:
				"Meet your audience where they are through SMS, WhatsApp, voice calls, video, or embed directly on your website with a single Digital Mind."
		},
		{
			title: "Stay current automatically",
			description:
				"Your Digital Mind learns continuously from new YouTube videos, podcasts, and content you create, ensuring answers always reflect your latest thinking."
		},
		{
			title: "Generate revenue on autopilot",
			description:
				"Monetize your expertise without hiring a team by capturing leads, scheduling consultations, and qualifying prospects while you focus on delivery."
		},
		{
			title: "Your mind remains yours",
			description:
				"Maintain complete ownership and control with encrypted storage, strict privacy standards, and the assurance your Digital Mind never improvises without consent."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop trading hours for dollars"
	subtitle="Start multiplying your impact"
	description="Join thousands of coaches and creators who've reclaimed 15+ hours weekly while deepening client relationships. Your Digital Mind handles repetitive questions with your authentic voice, so you can focus on the work only you can do. Arnold Schwarzenegger, Matthew Hussey, and Jay Shetty already trust Delphi to scale their wisdom."
	imageSrc="/generated/image-a-confident-coach-smiling-warmly-in-a-su.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Start scaling your wisdom",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
