<script>
</script>

<nav>
    <div class="nav-left">
        <a href="#presentation">Présentation</a>
        <a href="#methods">Méthodes</a>
    </div>
    <div class="nav-logo">
        <div class="nav-logo-full">
            <a href="#presentation"
                ><img src="img/logo-puppet.png" alt="puppet services" /></a
            >
        </div>
        <div class="nav-logo-small">
            <a href="#presentation"
                ><img src="img/logo-puppet-p.png" alt="puppet services" /></a
            >
        </div>
    </div>
    <div class="nav-right">
        <a class="references" href="#references">Références</a>
        <a class="contact" href="#contact">Contact</a>
    </div>
    <!-- Mobile -->
    <label for="toggle">Menu</label>
    <input type="checkbox" id="toggle">
    <div class="main-pages">
        <a href="#presentation">Présentation</a>
        <a href="#methods">Méthodes</a>
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
        transition: 0.5s;
    }

    a:hover {
        scale: 1.1;
        text-decoration: underline;
        transition: 0.5s;
    }

    /* Mobile */

    label, #toggle {
        position: fixed;
        color: var(--primary-color);
        font-size: 1.2rem;
        font-weight: bold;
        text-transform: uppercase;
        right: 10px;
        display: none;
    }

    .main-pages {
        position: fixed;
        top: 79px;
        right: 0px;
        background: var(--blur-color);
        backdrop-filter: blur(10px);
        padding: 10px;
        display: none;
    }

    #toggle:checked + .main-pages {
        display: flex;
        flex-direction: column;
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
        .references,
        .contact {
            display: none;
        }

        .nav-right {
            justify-content: end;
        }

        label {
            display: block;
        }
    }
</style>
