<script>
	import { Separator } from '$lib/components/ui/separator';
</script>

<div class="grid h-dvh place-content-center gap-14 p-2">
	<div class="grid gap-y-6">
		<h1 class="text-5xl font-medium">navtoj <span class="text-foreground/75">chahal</span></h1>
		<div class="grid gap-y-2 text-lg text-foreground/50">
			<p>I'm a programmer.</p>
			<p>Passionate about design and software.</p>
			<p>Currently studying computer science.</p>
		</div>
	</div>

	<div class="grid gap-y-4">
		<h1 class="text-3xl font-medium text-foreground/75">get in touch</h1>
		<Separator />
		<div class="flex justify-between gap-x-4 px-4 text-lg text-foreground/50">
			<a href="mailto:hello@navtoj.com" class="hover:text-foreground">email</a>
			<Separator orientation="vertical" />
			<a href="https://github.com/navtoj" class="hover:text-foreground">github</a>
			<Separator orientation="vertical" />
			<a href="https://twitter.com/navtoj" class="hover:text-foreground">twitter</a>
		</div>
	</div>

	<div class="grid gap-y-4">
		<h1 class="text-3xl font-medium text-foreground/75">past work</h1>
		<Separator />
		<div class="grid gap-y-3 text-lg text-foreground/50">
			<a
				class="group/link flex items-center justify-between px-2.5 py-1.5 hover:bg-gradient-to-r hover:from-yellow-500 hover:to-slate-50 hover:text-background"
				target="_blank"
				href="https://github.com/navtoj/notchbar"
			>
				<p>NotchBar</p>
				<p class="text-sm group-hover/link:text-yellow-500 dark:group-hover/link:text-background">
					2024
				</p>
			</a>
			<a
				class="group/link flex items-center justify-between px-2.5 py-1.5 hover:bg-gradient-to-r hover:from-emerald-400 hover:to-slate-50 hover:text-background"
				target="_blank"
				href="https://ufv.pages.dev"
			>
				<p>Scholarship Finder</p>
				<p
					class="group-hover/link:text-emerafrom-emerald-400 text-sm dark:group-hover/link:text-background"
				>
					2023
				</p>
			</a>
			<a
				class="group/link flex items-center justify-between px-2.5 py-1.5 hover:bg-gradient-to-r hover:from-blue-500 hover:to-slate-50 hover:text-background"
				target="_blank"
				href="https://www.apothefy.com"
			>
				<p>Apothefy</p>
				<p class="text-sm group-hover/link:text-blue-500 dark:group-hover/link:text-background">
					2022
				</p>
			</a>
			<a
				class="group/link flex items-center justify-between px-2.5 py-1.5 hover:bg-gradient-to-r hover:from-fuchsia-400 hover:to-slate-50 hover:text-background"
				target="_blank"
				href="https://www.spotcare.ca"
			>
				<p>SpotCare</p>
				<p class="text-sm group-hover/link:text-fuchsia-400 dark:group-hover/link:text-background">
					2021
				</p>
			</a>
		</div>
	</div>
</div>
