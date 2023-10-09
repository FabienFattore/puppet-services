<script></script>

<section id="references">
    <div class="references-text">
        <h1>Références</h1>
        <p>
            Voici quelques réalisations de Puppet Services.<br />
            Nous avons actuellement de beaux projets dans les tuyaux,<br />
            ET NOUS AVONS Hâte de les partager ici !
        </p>
    </div>
    <div class="slider-container">
        <div class="references-slider">
            <div class="references-slider-content">
                <img src="img/1.jpg" alt="puppet-services" /><img
                    src="img/2.jpg"
                    alt="puppet-services"
                /><img src="img/3.jpg" alt="puppet-services" /><img
                    src="img/4.jpg"
                    alt="puppet-services"
                /><img src="img/5.png" alt="puppet-services" /><img
                    src="img/6.png"
                    alt="puppet-services"
                />
            </div>
        </div>
    </div>
</section>

<style>
    section {
        display: flex;
        flex-direction: row-reverse;
        width: 100%;
    }

    .slider-container {
        width: 30vw;
        height: 50vh;
    }

    .references-text {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        color: aliceblue;
        background: rgb(88, 88, 88);
        background: radial-gradient(
            circle,
            rgba(88, 88, 88, 1) 0%,
            rgba(40, 40, 40, 1) 100%
        );
        width: 70vw;
        height: 50vh;
    }

    h1 {
        text-transform: uppercase;
    }

    .references-slider {
        max-width: 30vw;
        height: 50vh;
        overflow: hidden;
    }

    .references-slider-content {
        width: 180vw;
        height: 50vw;
        position: relative;
        animation-name: slider;
        animation-duration: 30s;
        animation-iteration-count: infinite;
        animation-direction: alternate-reverse;
    }

    img {
        width: 30vw;
        height: 50vh;
    }

    @keyframes slider {
        0% {
            left: 0px;
        }
        8% {
            left: 0px;
        }
        16% {
            left: -30vw;
        }
        24% {
            left: -30vw;
        }
        32% {
            left: -60vw;
        }
        40% {
            left: -60vw;
        }
        48% {
            left: -90vw;
        }
        56% {
            left: -90vw;
        }
        64% {
            left: -120vw;
        }
        72% {
            left: -120vw;
        }
        80% {
            left: -150vw;
        }
        100% {
            left: -150vw;
        }
    }
</style>
