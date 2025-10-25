<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconLayers from "~icons/lucide/layers";
	import IconZap from "~icons/lucide/zap";
	import IconShield from "~icons/lucide/shield";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconPlug from "~icons/lucide/plug";
</script>

<Hero
	centered={false}
	title="Automate workflows without writing code"
	subtitle="Connect your systems and eliminate repetitive tasks with pre-built templates trusted by operations teams at scaling companies"
	imageSrc="/generated/image-a-group-of-diverse-operations-team-membe.webp"
	callsToAction={[
		{
			href: "/start",
			label: "Start automating"
		},
		{
			href: "/templates",
			label: "Browse templates"
		}
	]}
/>
<LogoScroller
	label="Trusted by operations teams at"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/airtable.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/slack.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/webflow.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We build automated workflows that connect your systems and execute tasks without manual intervention or coding. Operations teams at scaling companies use our platform to eliminate repetitive processes through pre-built templates, freeing up time to focus on strategic work. Our AI-powered automation captures real business value by transforming hours of manual work into seconds of automated execution."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Director of Operations",
			company: "CoreLogic Systems",
			quote:
				"We eliminated 22 hours of manual data entry per week using their pre-built templates. What used to take our team three days now happens automatically overnight, freeing us to focus on strategic work that actually grows the business.",
			image: "/generated/image-confident-asian-woman-operations-manager.webp"
		},
		{
			name: "Marcus Williams",
			position: "VP of Operations",
			company: "Velocity Commerce",
			quote:
				"The integration templates saved us from a six-month custom development project. We connected our CRM, inventory system, and fulfillment platform in under two weeks, avoiding $180K in developer costs and getting to market faster than our competitors.",
			image: "/generated/image-confident-black-man-operations-director-.webp"
		},
		{
			name: "Layla Hassan",
			position: "Chief Operating Officer",
			company: "Nexus Financial",
			quote:
				"Manual process errors were costing us $40K monthly in corrective work. Their automated workflows reduced error rates by 94% in the first quarter, and our compliance team finally sleeps at night knowing critical data transfers happen reliably every single time.",
			image: "/generated/image-confident-middle-eastern-woman-business-.webp"
		}
	]}
/>

<Features
	title="Built for operations teams who need to move fast"
	subtitle="AI-powered automation that eliminates repetitive tasks without requiring technical expertise"
	features={[
		{
			title: "AI that learns your workflows",
			description:
				"Our AI analyzes your processes and automatically suggests optimizations, turning hours of manual work into minutes of intelligent automation.",
			icon: IconBrain
		},
		{
			title: "Pre-built templates for instant deployment",
			description:
				"Skip the setup with battle-tested workflow templates designed for common operations scenarios. Launch in minutes, not weeks.",
			icon: IconLayers
		},
		{
			title: "Zero coding required",
			description:
				"Build sophisticated automations through an intuitive interface that operations teams love. No developers needed, no technical barriers.",
			icon: IconZap
		},
		{
			title: "Enterprise-grade security",
			description:
				"Bank-level encryption and SOC 2 compliance built-in from day one. Your data stays secure as you scale.",
			icon: IconShield
		},
		{
			title: "Scales from 1 to 100,000 workflows",
			description:
				"Start small and grow without limits. Our infrastructure handles enterprise workloads while maintaining millisecond response times.",
			icon: IconTrendingUp
		},
		{
			title: "Connect everything in your stack",
			description:
				"Seamlessly integrate with 500+ tools and systems. From CRMs to databases, unify your operations in one powerful platform.",
			icon: IconPlug
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop wasting hours on manual tasks"
	subtitle="Start automating today"
	description="Your team is drowning in repetitive work while competitors move faster. Launch your first automated workflow in minutes with pre-built templates—no coding, no complex setup, no excuses. Join operations teams already saving 20+ hours per week."
	imageSrc="/generated/image-a-cheerful-operations-manager-celebratin.webp"
	callsToAction={[
		{
			href: "/start",
			label: "Start automating free",
			variant: "primary"
		},
		{
			href: "/templates",
			label: "Browse templates",
			variant: "secondary"
		}
	]}
/>
