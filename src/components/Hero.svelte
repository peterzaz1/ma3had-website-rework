<script>
	import uni from './../assets/logo1.png';
	import Button from './Button.svelte';
</script>

<section
	class="bg-neutral-800 shadow-lg flex py-24 flex-col items-center md:flex-row md:px-16 md:justify-between lg:px-28"
>
	<img src={uni} alt="uni" class=" md:m-0 w-44 md:w-56" />
	<div class=" text-white">
		<h1 class="text-4xl text-center mt-6 md:mt-0 md:text-right">المعهد العالي للدراسات النوعية</h1>
		<div class="flex flex-col justify-center items-center gap-4 md:items-end">
			<div class="flex justify-center items-center md:justify-end">
				<span
					><svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24"
						><path
							d="M480-480q33 0 56.5-23.5T560-560q0-33-23.5-56.5T480-640q-33 0-56.5 23.5T400-560q0 33 23.5 56.5T480-480Zm0 294q122-112 181-203.5T720-552q0-109-69.5-178.5T480-800q-101 0-170.5 69.5T240-552q0 71 59 162.5T480-186Zm0 106Q319-217 239.5-334.5T160-552q0-150 96.5-239T480-880q127 0 223.5 89T800-552q0 100-79.5 217.5T480-80Zm0-480Z"
						/></svg
					></span
				>
				<p class="pt-3">مصر، الجيزة</p>
			</div>
			<div class="flex gap-7">
				<a href="/sign-in">
					<Button>صفحة الطالب</Button>
				</a>

				<Button>الاتصال بنا</Button>
			</div>
		</div>
	</div>
</section>

<!-- #BF9270 -->
