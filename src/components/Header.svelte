<script>
	import logo from './../assets/logo-fire3.png';
	import manu from './../assets/manu.png';
	let navList;
	function handleToggle() {
		if (navList.classList.contains('top-[-100%]')) {
			navList.classList.remove('top-[-100%]');
			navList.classList.add('top-[72px]');
		} else {
			navList.classList.remove('top-[72px]');
			navList.classList.add('top-[-100%]');
		}
	}
</script>

<header class="py-2 bg-[#ddd3b8]">
	<nav class="flex justify-between w-[92%] m-auto items-center">
		<div>
			<a href="/">
				<img src={logo} alt="logo" class="w-12" />
			</a>
		</div>

		<div
			bind:this={navList}
			class="absolute w-full h-full right-0 top-[-100%] bg-[#ddd3b8]/50 backdrop-blur md:static md:border-0 md:h-fit md:w-auto"
		>
			<ul class="flex flex-col items-center text-black md:gap-[4vw] md:flex-row gap-10 py-4">
				<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
					>نبذه عنا</a
				>
				<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
					>الخدمات</a
				>
				<a href="/sign-in" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
					>صفحة الطالب</a
				>
				<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
					>الرئيسيه</a
				>
			</ul>
		</div>
		<div class="flex items-center gap-4">
			<button class="text-2xl px-2 py-2 bg-[#fb8b24ff] text-white rounded-md hover:bg-[#e36414ff]"
				>الاتصال بنا</button
			>
			<button on:click={handleToggle}
				><img src={manu} alt="manu" class="w-9 h-6 md:hidden" /></button
			>
		</div>
	</nav>
</header>
