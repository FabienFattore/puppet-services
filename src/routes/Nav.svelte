<script>
    import Style from "../params/Style.svelte";
</script>

<nav>
    <div class="nav-left">
        <a href="#presentation">Présentation</a>
        <a href="#methods">Méthodes</a>
    </div>
    <div class="nav-logo">
        <img src="img/logo-puppet.png" alt="puppet services" />
    </div>
    <div class="nav-right">
        <a href="#references">Références</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<style>
    nav {
        position: fixed;
        top: 0;
        background: var(--blur-color);
        backdrop-filter: blur(10px);
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        z-index: 2;
    }

    .nav-left,
    .nav-right {
        width: 30%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin: 0 2%;
    }

    .nav-logo img {
        width: 150px;
    }

    a {
        color: var(--primary-color);
        text-decoration: none;
        font-weight: bold;
        font-size: 1.2rem;
        text-transform: uppercase;
    }
</style>
