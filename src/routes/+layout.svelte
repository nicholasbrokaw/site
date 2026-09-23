<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();

	const siteName = 'Nicholas Brokaw';
	const title = 'Nicholas Brokaw — Software developer, entrepreneur, co-founder';
	const description =
		'Nicholas Brokaw is a software developer and entrepreneur, co-founder of Identechal and Eripio Coffee. Based online at nicholasbrokaw.com.';
	const siteUrl = 'https://nicholasbrokaw.com';
	const imageUrl = `${siteUrl}/nicholas.jpg`;

	const structuredData = {
		'@context': 'https://schema.org',
		'@type': 'Person',
		name: 'Nicholas Brokaw',
		url: siteUrl,
		image: imageUrl,
		jobTitle: 'Software Developer',
		description: 'Software developer and entrepreneur; co-founder of Identechal and Eripio Coffee.',
		email: 'mailto:nicholasbrokaw@hey.com',
		sameAs: ['https://linkedin.com/in/nicholasbrokaw', 'https://github.com/nicholasbrokaw'],
		knowsAbout: [
			'Software development',
			'Entrepreneurship',
			'Coffee',
			'Music',
			'Fighting human trafficking'
		],
		affiliation: [
			{
				'@type': 'Organization',
				name: 'Identechal',
				url: 'https://identechal.com'
			},
			{
				'@type': 'Organization',
				name: 'Eripio Coffee',
				url: 'https://eripio.store'
			}
		],
		sibling: {
			'@type': 'Person',
			name: 'Jacob Brokaw',
			url: 'https://jacobbrokaw.com'
		}
	};
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />
	<link rel="canonical" href={siteUrl} />
	<link rel="human-json" href="/human.json" type="application/json" />
	<link rel="icon" href={favicon} type="image/svg+xml" />
	<meta name="theme-color" content="#f7f5f2" />
	<meta name="author" content="Nicholas Brokaw" />

	<meta property="og:type" content="profile" />
	<meta property="og:site_name" content={siteName} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={description} />
	<meta property="og:url" content={siteUrl} />
	<meta property="og:image" content={imageUrl} />
	<meta property="og:locale" content="en_US" />
	<meta property="profile:first_name" content="Nicholas" />
	<meta property="profile:last_name" content="Brokaw" />

	<meta name="twitter:card" content="summary" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={description} />
	<meta name="twitter:image" content={imageUrl} />

	<meta name="robots" content="index,follow" />

	{@html `<script type="application/ld+json">${JSON.stringify(structuredData)}</script>`}
</svelte:head>

{@render children()}
