<script>
	import about1 from './../assets/about-1.jpg';
	import about2 from './../assets/about-2.jpg';
	import about3 from './../assets/about-3.jpg';
	import AboutMini from './AboutMini.svelte';
</script>

<section class="pb-20 bg-[#ddd3b8]">
	<div class="px-8 text-center flex flex-col items-center">
		<div class="my-5 mb-10 border-neutral-900 border-b-2 py-4">
			<h2 class="text-4xl">نبذه عن المعهد</h2>
		</div>
		<p class="text-xl">
			ومنذ نشاءت المعهد عام 1995 تعمل ادارتة على تكريس كافة الامكانيات الماديه والبشرية لتحقيق هذا
			الهدف من خلال تكاتف كادفة الجهود سواء من قبل مجلس الادارة او اعضاء هيئية التدريس او اولياء
			الامور وتوصلت إدارة المعهد إلى اختيار أربع تخصصات علمية رفيعة و هي : الدراسات السياحية (
			الدراسات السياحة – إدارة الفنادق – الإرشاد السياحي) نظم المعلومات الإدارية- اللغات و الترجمة-
			العلوم التجارية
		</p>
	</div>
	<div class="flex justify-center">
		<div class="grid-cols-1 grid grid-flow-row-dense mx-2 mt-20 gap-10 md:gap-20 md:grid-cols-2">
			<AboutMini
				title="قسم نظم المعلومات الادارية"
				aboutImg={about1}
				paragraph="معادلة الشهادات التي يمنحها القسم بدرجة البكالوريوس التي تمنحها الجامعات المصرية، و ذلك بموجب القرار الوزاري رقم 266"
			/>
			<AboutMini
				title="العلوم التجارية"
				aboutImg={about1}
				paragraph="تمت معادلة الشهادات التى يمنحها - قسم العلوم التجارية (إدارة اعمال – محاسبة) قرار المعادلة رقم ١٢ طابع تنسيق ٣٢٨ /"
			/>
			<AboutMini
				title="اللغات والترجمة"
				aboutImg={about2}
				paragraph="تمت معادلة الشهادات التى يمنحها - قسم اللغات والترجمة قرار المعادلة رقم ٨٠ – طابع تنسيق ٣٢٩/٨"
			/>
			<AboutMini
				title="الدراسات السياحية"
				aboutImg={about3}
				paragraph="تمت معادلة الشهادات التى يمنحها قسم الدراسات السياحية (الدراسات السياحية – إدارة الفنادق- ارشاد سياحي ) قرار المعادلة رقم ٤٧ - طابع تنسيق رقم ٣٣٦"
			/>
		</div>
	</div>
</section>
