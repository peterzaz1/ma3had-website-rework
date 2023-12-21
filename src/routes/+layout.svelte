<script>
	import '../app.css';
	import Footer from '../components/Footer.svelte';
	import Header from '../components/Header.svelte';
	import StickyHeader from '../components/StickyHeader.svelte';
</script>

<!-- <Header /> -->
<StickyHeader />
<slot />
<Footer />
