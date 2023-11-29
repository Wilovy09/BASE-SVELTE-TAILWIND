<script>
    // Tailwind CSS
    import "../app.css";
    // Componentes
    import Navbar from "../components/_Navbar.svelte";
    import Footer from "../components/_Footer.svelte";
</script>

<main>
    <Navbar />
    <section>
        <slot></slot>
    </section>
    <Footer />
</main>

<style>
    
</style>