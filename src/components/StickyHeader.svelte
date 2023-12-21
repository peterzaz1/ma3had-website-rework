<script>
	import logo from './../assets/logo-fire3.png';
	import menu from './../assets/manu.png';
	let showMenu = false;
	function handleMenu() {
		showMenu = !showMenu;
	}
</script>

<header class="fixed w-full z-50">
	<nav class="flex items-center p-4 bg-[#ddd3b8] justify-between">
		<div>
			<a href="/">
				<img src={logo} alt="logo" class="w-12" />
			</a>
		</div>
		<div class={` ${showMenu ? 'block' : 'hidden'}  md:block`}>
			<ul
				class={`flex gap-8 items-center ${
					showMenu
						? 'absolute pt-12 flex-col gap-15 top-[77px] backdrop-blur left-0 h-[100vh] w-full bg-[#ddd3b8]/50'
						: ''
				} `}
			>
				<li>
					<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
						>نبذه عنا</a
					>
				</li>
				<li>
					<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
						>الخدمات</a
					>
				</li>
				<li>
					<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
						>صفحة الطالب</a
					>
				</li>
				<li>
					<a href="/" class="text-2xl hover:text-gray-400 border-b-2 border-black md:border-0"
						>الرئيسيه</a
					>
				</li>
			</ul>
		</div>
		<div class="flex gap-4 items-center">
			<button class="bg-[#fb8b24ff] text-white py-2 px-4 rounded-sm">الاتصال بنا</button>
			<button class="w-9 h-9 md:hidden" on:click={handleMenu}><img src={menu} alt="" /></button>
		</div>
	</nav>
</header>
