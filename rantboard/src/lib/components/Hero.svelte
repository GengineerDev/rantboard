<script>
    import Button from "./Button.svelte";

</script>

<section class="hero">

    <h1>Rant freely!</h1>
    <p>This is a place where no one will judge you. Scream your heart out!</p>    
    <Button>Post Now!</Button>
</section>

<style>
    .hero {
        background-color: var(--defaultGray);
        text-align: center;
        padding: 15rem 0;
    }

    .hero h1 {
        font-size: 36px;
        color: var(--black);
    }

    .hero p {
        color: var(--grey);
        font-weight: 400;
        font-size: 20px;
        margin: 1rem 0;
    }
    
</style>