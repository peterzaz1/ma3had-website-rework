<script>
	import img from './../assets/sec1.jpeg';
	import img2 from './../assets/sec2.jpeg';
	import img3 from './../assets/sec3.jpeg';
	import ParagraphImage from './ParagraphImage.svelte';
	let title = 'رؤية المعهد';
	let paragraph =
		'يسعي المعهد لتحقيق التميز  والريادة في مجال التعليم التجاري والسياحي ونظم المعلومات الادارية واللغات والترجمة من خلال الالتزام بمقومات الجودة في ظل بيئة علمية وثقافية وقيمية داعمة لتلبية متطلبات سوق العمل المحلي والاقليمي والعالمي .  ';
	let title2 = 'رسالة المعهد';
	let paragraph2 =
		'يلتزم المعهد باعداد خريج مهنى تنافسى في المجالات الاربع ( العلوم التجارية - الدراسات السياحية - نظم المعلومات الادارية - اللغات والترجمة ) وقادر على مواكبة سوق العمل على المستوى المحلى والاقليمى والدولى والمساهمة في النشاط البحثى وخدمة المجتمع.';
	let paragraph3 =
		'يقوم المعهد بإعداد خريجين متميزين  في المجالات التجارية والسياحية و اللغات للمنافسة في سوق العمل المحلي والاقليمي  والمساهمة في خدمة المجتمع وبما يتفق مع رسالة وزارة التعليم العالي. ';
</script>

<main class="">
	<ParagraphImage {title} {paragraph} {img} dir={'rtl'} bg={'bg-[#d5bdaf]'} />
	<ParagraphImage
		title={title2}
		paragraph={paragraph2}
		img={img2}
		dir={'ltr'}
		bg={'bg-[#e3d5ca]'}
	/>
	<ParagraphImage paragraph={paragraph3} img={img3} dir={'rtl'} bg={'bg-[#d5bdaf]'} />
</main>
