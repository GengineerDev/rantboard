<nav>
    <div>
        <img src="/images/logo.png" alt="Rantboard Logo" class="logo"/>
    </div>
    <div class="pages">
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/contact">Contact</a>
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
    }

    .pages {
        display: flex;
        align-items: center;
        gap: 50px;
        border: 1px solid black;
        width: 100%;
        height: 100%;
    }

    nav > div:first-child {
        display: flex;
    }

    .logo {
        height: 36px; 
        align-self: center;
        padding-left: 95px;
    }
</style>
