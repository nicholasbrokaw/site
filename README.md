# nicholasbrokaw.com

Personal site for Nicholas Brokaw. Built with the same stack as [Identechal](https://identechal.com): SvelteKit, Tailwind CSS, and Cloudflare (Wrangler).

## Developing

```sh
npm install
npm run dev -- --open
```

## Building

```sh
npm run build
npm run preview
```

## Deploy

```sh
npx wrangler deploy
```

## Recreate

```sh
npx sv@0.17.0 create --template minimal --types ts --add tailwindcss="plugins:none" sveltekit-adapter="adapter:cloudflare+cfTarget:workers" prettier eslint --install npm nicholasbrokaw-site
```
