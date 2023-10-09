<script>
    import Style from "../params/Style.svelte";
</script>

<nav>
    <div class="nav-left">
        <a href="#presentation">Présentation</a>
        <a href="#methods">Méthodes</a>
    </div>
    <div class="nav-logo">
        <div class="nav-logo-full">
            <img src="img/logo-puppet.png" alt="puppet services" />
        </div>
        <div class="nav-logo-small">
            <img src="img/logo-puppet-p.png" alt="puppet services" />
        </div>
    </div>
    <div class="nav-right">
        <a class="references" href="#references">Références</a>
        <a class="contact" href="#contact">Contact</a>
        <a class="menu" href=" ">Menu</a>
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

    .menu {
        display: none;
    }

    .nav-logo-small img {
        width: 40px;
    }

    .nav-logo-small {
        display: none;
    }

    .nav-logo-full img {
        width: 150px;
    }

    a {
        color: var(--primary-color);
        text-decoration: none;
        font-weight: bold;
        font-size: 1.2rem;
        text-transform: uppercase;
    }

    @media screen and (max-width: 1024px) {
        .nav-logo-small {
            display: block;
        }

        .nav-logo-full {
            display: none;
        }

        .nav-left,
        .nav-right {
            width: 40%;
        }
    }

    @media screen and (max-width: 768px) {
        .nav-logo-small {
            margin-left: 10px;
        }

        .nav-left,
        .references, .contact {
            display: none;
        }

        .nav-right {
            justify-content: end;
        }

        .menu  {
            display: block !important;
        }
    }
</style>
