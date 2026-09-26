<script lang="ts">
	const email = 'nicholasbrokaw@hey.com';
	const mailto = `mailto:${email}`;
	const year = new Date().getFullYear();
</script>

<div class="iridescent-stage flex min-h-dvh flex-col">
	<a
		href="#main"
		class="sr-only focus:not-sr-only focus:absolute focus:top-4 focus:left-4 focus:z-50 focus:rounded focus:bg-white focus:px-3 focus:py-2 focus:text-sm focus:text-ink focus:shadow"
	>
		Skip to content
	</a>

	<main
		id="main"
		class="mx-auto flex w-full max-w-5xl flex-1 flex-col justify-center px-6 py-16 sm:px-10 sm:py-24"
	>
		<section
			class="grid items-center gap-12 md:grid-cols-[minmax(0,14rem)_minmax(0,1fr)] md:gap-16 lg:grid-cols-[minmax(0,16rem)_minmax(0,1fr)]"
		>
			<div class="flex justify-center md:justify-start">
				<div class="portrait-frame w-44 sm:w-52 md:w-full md:max-w-[16rem]">
					<img
						src="/nicholas.jpg"
						alt="Portrait of Nicholas Brokaw"
						width="1536"
						height="1536"
						decoding="async"
						fetchpriority="high"
					/>
				</div>
			</div>

			<div class="max-w-xl text-center md:text-left">
				<p
					class="name-wordmark mb-3 text-sm font-medium tracking-[0.28em] text-ink uppercase sm:text-base"
				>
					Nicholas Brokaw
				</p>

				<h1
					class="text-2xl leading-snug font-medium text-balance text-ink sm:text-3xl sm:leading-snug"
				>
					Nice to meet you. I'm a software developer and entrepreneur.
				</h1>

				<div class="mt-6 space-y-5 text-lg leading-relaxed text-pretty text-ink-soft sm:text-xl">
					<p>
						I co-founded
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://identechal.com"
							target="_blank"
							rel="noopener noreferrer"
							title="Identechal">Identechal</a
						>
						with my twin,
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://jacobbrokaw.com"
							target="_blank"
							rel="noopener noreferrer"
							title="Jacob Brokaw">Jacob</a
						>
						— we build websites and software for small-to-medium sized businesses.
					</p>

					<p>
						I'm also a co-founder of
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://eripio.store"
							target="_blank"
							rel="noopener noreferrer"
							title="Eripio Coffee">Eripio</a
						>, a coffee company fighting human trafficking. Order a bag and read the story at
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://eripio.store"
							target="_blank"
							rel="noopener noreferrer">eripio.store</a
						>.
					</p>

					<p>
						Outside of work I love coffee and music — especially artists like
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://www.thylacinemusic.com"
							target="_blank"
							rel="noopener noreferrer"
							title="Thylacine">Thylacine</a
						>, who is a real inspiration.
					</p>

					<p>
						Say hello at
						<a class="text-link font-medium text-ink underline decoration-ink/30" href={mailto}
							>{email}</a
						>, or find me on
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://linkedin.com/in/nicholasbrokaw"
							target="_blank"
							rel="noopener noreferrer"
							title="LinkedIn">LinkedIn</a
						>
						and
						<a
							class="text-link font-medium text-ink underline decoration-ink/30"
							href="https://github.com/nicholasbrokaw"
							target="_blank"
							rel="noopener noreferrer"
							title="GitHub">GitHub</a
						>.
					</p>
				</div>

				<div class="mt-10 flex flex-col items-center gap-4 sm:flex-row md:justify-start">
					<a
						href={mailto}
						class="inline-flex items-center justify-center rounded-full bg-ink px-6 py-3 text-sm font-medium tracking-wide text-paper transition hover:bg-ink-soft focus-visible:outline-2 focus-visible:outline-offset-4 focus-visible:outline-sea"
					>
						Email me
					</a>

					<div class="flex items-center gap-3">
						<a
							class="social-icon"
							href="https://github.com/nicholasbrokaw"
							target="_blank"
							rel="noopener noreferrer"
							title="GitHub"
							aria-label="GitHub"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 24 24"
								width="18"
								height="18"
								fill="currentColor"
								aria-hidden="true"
							>
								<path
									d="M12 2C6.477 2 2 6.586 2 12.253c0 4.53 2.865 8.367 6.839 9.722.5.094.683-.222.683-.493 0-.243-.009-.886-.014-1.738-2.782.618-3.369-1.38-3.369-1.38-.455-1.183-1.11-1.498-1.11-1.498-.908-.638.069-.625.069-.625 1.004.072 1.532 1.06 1.532 1.06.892 1.57 2.341 1.116 2.91.854.091-.662.35-1.116.636-1.372-2.22-.26-4.555-1.143-4.555-5.087 0-1.124.39-2.043 1.029-2.764-.103-.26-.446-1.302.098-2.714 0 0 .84-.276 2.75 1.055A9.3 9.3 0 0 1 12 6.912a9.3 9.3 0 0 1 2.504.346c1.909-1.331 2.747-1.055 2.747-1.055.546 1.412.203 2.454.1 2.714.64.721 1.028 1.64 1.028 2.764 0 3.953-2.338 4.823-4.566 5.079.359.317.679.943.679 1.901 0 1.372-.012 2.477-.012 2.814 0 .273.18.592.688.491C19.138 20.617 22 16.78 22 12.253 22 6.586 17.523 2 12 2Z"
								/>
							</svg>
						</a>
						<a
							class="social-icon"
							href="https://linkedin.com/in/nicholasbrokaw"
							target="_blank"
							rel="noopener noreferrer"
							title="LinkedIn"
							aria-label="LinkedIn"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 24 24"
								width="18"
								height="18"
								fill="currentColor"
								aria-hidden="true"
							>
								<path
									d="M19.75 3H4.25A1.25 1.25 0 0 0 3 4.25v15.5A1.25 1.25 0 0 0 4.25 21h15.5A1.25 1.25 0 0 0 21 19.75V4.25A1.25 1.25 0 0 0 19.75 3ZM8.34 18.34H5.67V9.75h2.67v8.59ZM7 8.57a1.55 1.55 0 1 1 0-3.1 1.55 1.55 0 0 1 0 3.1Zm11.34 9.77h-2.67v-4.6c0-1.1-.02-2.51-1.53-2.51-1.53 0-1.77 1.2-1.77 2.43v4.68h-2.67V9.75h2.56v1.17h.04c.36-.68 1.23-1.4 2.53-1.4 2.7 0 3.2 1.78 3.2 4.09v4.73Z"
								/>
							</svg>
						</a>
					</div>
				</div>
			</div>
		</section>
	</main>

	<footer class="px-6 pb-8 sm:px-10 sm:pb-10">
		<div
			class="mx-auto flex max-w-5xl flex-col items-center justify-between gap-3 text-center text-sm text-ink-soft sm:flex-row sm:text-left"
		>
			<p>&copy; {year} Nicholas Brokaw</p>
			<div class="flex flex-wrap items-center justify-center gap-x-4 gap-y-1 sm:justify-end">
				<a
					class="text-link underline decoration-ink/25"
					href="https://identechal.com"
					target="_blank"
					rel="noopener noreferrer">Identechal</a
				>
				<a
					class="text-link underline decoration-ink/25"
					href="https://eripio.store"
					target="_blank"
					rel="noopener noreferrer">Eripio</a
				>
				<a class="text-link underline decoration-ink/25" href={mailto}>{email}</a>
			</div>
		</div>
	</footer>
</div>
