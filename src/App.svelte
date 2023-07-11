<script>
	import NavBar from './Components/NavBar.svelte'
	import Content from './Components/Content.svelte'
	import Footer from './Components/Footer.svelte';
    import ReadBlog from './Pages/ReadBlog.svelte';
</script>

<!-- <ReadBlog /> -->
<div class="finsweetBlog">
	<NavBar />

<Content />
<Footer />
</div>
<style>

	/* main { */
		/* text-align: center; */
		/* padding: 1em;
		max-width: 240px;
		margin: 0 auto; */

	/* } */


	/* @media (min-width: 640px) {
		main {
			max-width: none;
		}
	} */

	.finsweetBlog{
		max-width: 1278px;
		width: 100%;
		margin-left: auto;
		margin-right: 
		auto;
	}
</style>