<script lang="ts">
	export let dark: boolean = false
</script>

<div class="flex items-center gap-4">
	<button class={"specialBtn " + dark ? " bg-[#181b34] text-white" : ""}>
		<p class="text-base sm:text-lg md:text-xl">Contact Us</p>
	</button>
	<button class={"specialBtnDark"}>
		<p class="text-base sm:text-lg md:text-xl">Get Started &rarr;</p>
	</button>
</div>
