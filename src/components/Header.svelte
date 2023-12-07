<script>
	import logo from './../assets/logo1.png';
	import manu from './../assets/manu.png';
	let navList;
	function handleToggle() {
		if (navList.classList.contains('top-[-100%]')) {
			navList.classList.remove('top-[-100%]');
			navList.classList.add('top-[10%]');
		} else {
			navList.classList.remove('top-[10%]');
			navList.classList.add('top-[-100%]');
		}
	}
</script>

<header class="py-3 bg-white">
	<nav class="flex justify-between w-[92%] m-auto items-center">
		<div>
			<a href="/">
				<img src={logo} alt="logo" class="w-12" />
			</a>
		</div>
		<div
			bind:this={navList}
			class="absolute bg-white w-full left-0 top-[-100%] md:static md:h-fit md:w-auto"
		>
			<ul class="flex flex-col items-center md:gap-[4vw] md:flex-row gap-10 py-4">
				<a href="/" class="text-2xl hover:text-gray-400">نبذه عنا</a>
				<a href="/" class="text-2xl hover:text-gray-400">الخدمات</a>
				<a href="/students" class="text-2xl hover:text-gray-400">صفحة الطالب</a>
				<a href="/" class="text-2xl hover:text-gray-400">الرئيسيه</a>
			</ul>
		</div>
		<div class="flex items-center gap-4">
			<button class="text-2xl px-2 py-2 bg-[#687EFF] text-white rounded-md hover:bg-indigo-500"
				>الاتصال بنا</button
			>
			<button on:click={handleToggle}
				><img src={manu} alt="manu" class="w-9 h-6 md:hidden" /></button
			>
		</div>
	</nav>
</header>
