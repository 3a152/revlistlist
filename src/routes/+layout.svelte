<script>
	import favicon from '$lib/assets/favicon.svg';
	import "./styles/style.css"

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
</svelte:head>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
	<div class="container d-flex justify-content-between align-items-center">
     <a class="navbar-brand" href="/">
	 <img src="/images/logo.png" alt="logo" height="30" class="me-2">Revival List List
	</a>

	<div class="d-flex align-items-center">
<a class="btn btn-primary mx-2" href="/credits">Credits</a>
<a href="/list" class="btn btn-primary mx-2">List</a>
<a href="/gallery" class="btn btn-primary mx-2">Gallery</a>
<a href="/clicker" class="btn btn-primary mx-2">Clicker</a>
	</div>
	</div>
</nav>


{@render children()}
