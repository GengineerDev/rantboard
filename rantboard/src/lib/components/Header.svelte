<script>
    import Button from "./Button.svelte";
</script>

<nav>
    <div>
        <a href="/" class="logo">
            <img src="/images/logo.png" alt="Rantboard Logo" height="36px"/>
        </a>        
    </div>
    <div class="pages">
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/contact">Contact</a>
        <Button>Sign Up/Login</Button>
    </div>
</nav>

<style>
    nav {
        background-color: var(--defaultGray);
        height: 86px;
        font-size: 20px;
        font-weight: 700;
        display: grid;
        grid-template-columns: 60% 40%;
        grid-template-rows: 100%; 
        color: var(--black);
        box-shadow: 4px 6px 13px 0px rgba(215, 215, 215, 0.25);
    }

    .pages {
        display: flex;
        align-items: center;
        gap: 50px;
        width: 100%;
        height: 100%;
    }

    nav > div:first-child {
        display: flex;
    }

    .logo {
        align-self: center;
        padding-left: 95px;
    }
</style>
