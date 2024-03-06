<script lang="ts">
    let showing = true;
</script>
<div
	id="ab-full-width-with-dismiss-button-on-blue-bg"
    hidden={!showing}
	class="bg-slate-950 hs-removing:-translate-y-full"
>
	<div class="max-w-[85rem] px-4 py-4 sm:px-6 lg:px-8 mx-auto">
		<div class="flex">
			<p class="text-white">
				This website is an absolute joke. Don't take it with a grain of salt. Instead, take it with
				a whole salt shaker.
			</p>

			<div class="ps-3 ms-auto">
				<button
					type="button"
					class="inline-flex rounded-lg p-1.5 text-white/[.8] hover:text-white focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-blue-600 focus:ring-white"
					data-hs-remove-element="#ab-full-width-with-dismiss-button-on-blue-bg"
                    on:click={() => (showing = false)}
				>
					<span class="sr-only">Dismiss</span>
					<svg
						class="flex-shrink-0 size-4"
						xmlns="http://www.w3.org/2000/svg"
						width="24"
						height="24"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="2"
						stroke-linecap="round"
						stroke-linejoin="round"><path d="M18 6 6 18" /><path d="m6 6 12 12" /></svg
					>
				</button>
			</div>
		</div>
	</div>
</div>
