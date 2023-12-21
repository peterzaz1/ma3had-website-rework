<script>
	export let aboutImg;
	export let title;
	export let paragraph;
</script>

<div
	class=" w-[80%] h-auto m-auto bg-[#cea686] rounded-md shadow-lg text-center md:m-0 md:w-80 md:h-96"
>
	<img src={aboutImg} alt="" class="rounded-t-md" />
	<div class="p-4">
		<h3 class="text-xl font-bold mb-5">{title}</h3>
		<p class="">
			{paragraph}
		</p>
	</div>
</div>
