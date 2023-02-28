<script>
	import About from './About.svelte';
	import Contact from './Contact.svelte';
	import ContactSimple from './ContactSimple.svelte';
	import Home from './Home.svelte';
	import LayoutBlack from './LayoutBlack.svelte';
	import OurClients from './OurClients.svelte';
	import RecentProjects from './RecentProjects.svelte';
	import VideoHighlights from './VideoHighlights.svelte';
</script>

<svelte:head>
	<title>Artica group</title>
	<meta name="description" content="Us work in seo, marketing digital, photografy an more" />
</svelte:head>

<Home />
<About />
<OurClients />
<LayoutBlack>
	<VideoHighlights />
	<RecentProjects />
	<Contact />
</LayoutBlack>
<ContactSimple />
