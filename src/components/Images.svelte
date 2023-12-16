<script>
	import pic1 from './../assets/pic1.jpg';
	import pic2 from './../assets/pic2.jpg';
	import pic3 from './../assets/pic3.jpg';
	import pic4 from './../assets/pic4.jpg';
	import pic5 from './../assets/pic5.jpg';
	import pic6 from './../assets/pic6.jpg';
</script>

<section class=" pb-20 flex flex-col justify-center bg-[#f1e6ca] items-center">
	<div class="my-5 mb-10 border-b-2 py-4 border-neutral-500">
		<h2 class="text-4xl">صور المعهد</h2>
	</div>
	<div class=" grid-cols-1 grid grid-flow-row-dense mx-2 mt-4 gap-5 md:grid-cols-2 lg:grid-cols-3">
		<img src={pic1} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
		<img src={pic2} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
		<img src={pic3} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
		<img src={pic4} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
		<img src={pic5} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
		<img src={pic6} alt="img" class=" w-[80vw] md:w-96 rounded-md drop-shadow-2xl" />
	</div>
</section>
