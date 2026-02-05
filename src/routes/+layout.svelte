<script>
	import favicon from '$lib/assets/favicon.png';
	import "./styles/style.css"

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link href="https://bootswatch.com/5/lumen/bootstrap.css" rel="stylesheet">
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
</svelte:head>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
	<div class="container d-flex justify-content-between align-items-center">
     <a class="navbar-brand" href="/">
	 <img src="/images/favicon.png" alt="logo" height="30" class="me-2 rounded">Revival List List
	</a>

	<div class="d-flex align-items-center">
<a class="btn btn-primary mx-2" href="/credits">Credits</a>
<a href="/list" class="btn btn-primary mx-2">List</a>
<a href="/gallery" class="btn btn-primary mx-2">Gallery</a>
<a href="https://discord.gg/w57d88V7TE" class="btn btn-primary mx-2">Discord</a>

<a href="https://archive.org/details/videoplayback_20251214_1433" class="btn btn-primary mx-2">itteh's retirement</a>

	</div>
	</div>
</nav>


{@render children()}
