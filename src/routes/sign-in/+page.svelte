<script>
	import img from './../../assets/stud.png';
	import Button from '../../components/Button.svelte';
</script>

<div class="flex flex-col justify-center items-center bg-neutral-200 h-[100vh]">
	<img src={img} alt="" class="w-72 mt-5" />
	<h1 class="text-2xl">المعهد العالي للدراسات النوعية</h1>
	<div class="bg-neutral-800 min-w-[320px] max-w-md w-[70%] h-52 rounded-3xl mt-8">
		<form action="" class="flex flex-col items-center justify-center px-10 pt-4 gap-3 text-white">
			<label for="code"> كود الطالب </label>
			<input
				type="text"
				placeholder="كود الطالب"
				class="py-2 text-center rounded-lg w-[60%] min-w-[200px] text-black"
			/>
			<button class="py-2 px-3 bg-blue-900 rounded-md mt-4">تسجيل دخول</button>
		</form>
	</div>
</div>
