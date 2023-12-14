<script>
	export let title = '';
	export let paragraph;
	export let img;
	export let dir;
	export let bg;
	export let textColor = 'text-black';
</script>

<section
	class={`flex flex-col justify-between ${bg} ${textColor} py-20 px-10 gap-5 border border-black/30 lg:gap-32 lg:px-20 
  ${dir === 'ltr' ? 'md:flex-row-reverse' : 'md:flex-row'}
`}
>
	<div class="flex justify-center items-center">
		<img src={img} alt="" class=" w-[100%] md:min-w-[400px] md:w-96 rounded-lg" />
	</div>
	<div class="flex flex-col justify-center items gap-8 text-center">
		{#if title}
			<h2 class="text-4xl">{title}</h2>
		{/if}
		<p class="text-xl">{paragraph}</p>
	</div>
</section>
