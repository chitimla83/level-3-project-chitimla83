<script>
  import "../app.scss"
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
</script>

<Nav />
<Header title="Craighead Diocesan School" subtitle="Sports Portal" />
<slot />
<Footer />
