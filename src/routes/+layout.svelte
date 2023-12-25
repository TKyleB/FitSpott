<script>
    import "bootstrap/dist/css/bootstrap.min.css"
    import scriptSrc from 'bootstrap/dist/js/bootstrap.bundle.js?url'
    import Navbar from "$lib/Components/Navbar.svelte";
</script>
<svelte:head>
    <script src="{scriptSrc}"></script>
</svelte:head>
<Navbar />
<slot></slot>