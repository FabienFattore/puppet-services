<script></script>

<section id="contact">
    <div class="contact-headband">
        <p>
            Vous rêvez d'avoir la vôtre ? Alors n'hésitez pas à nous contacter !
        </p>
    </div>
    <div class="contact-form-container">
        <h1>CONTACTEZ-NOUS</h1>
        <p>
            Pour nous écrire, remplissez le formulaire de contact ci-dessous ou
            joignez Mehdi au 06 33 17 29 85 !
        </p>
        <form action="">
            <input type="text" placeholder="votre nom" />
            <input type="email" placeholder="votre e-mail" />
            <textarea
                name="message"
                id=""
                cols="30"
                rows="10"
                placeholder="Votre message"
            />
            <button>Envoyer</button>
        </form>

    </div>
</section>

<style>
    section {
        background: url(img/fleece2.jpg) fixed;
        display: flex;
        flex-direction: column;
        width: 100%;
    }

    .contact-headband {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        width: 100%;
        height: 120px;
        background: rgb(45, 131, 138);
        background: radial-gradient(
            circle,
            rgba(45, 131, 138, 1) 0%,
            rgba(0, 118, 127, 1) 100%
        );
    }

    p {
        color: var(--third-color);
    }

    .contact-form-container p {
        color: var(--secondary-color);
    }

    .contact-form-container {
        padding: 70px 0;
        display: flex;
        flex-direction: column;
        margin: auto;
        width: 70%;
    }

    h1 {
        color: var(--primary-color);
    }

    form {
        margin: 20px 0;
        display: flex;
        flex-direction: column;
    }

    input {
        width: 100%;
        padding: 10px 0 10px 5px;
        margin-bottom: 15px;
        border: none;
        box-shadow: gray 0px 0px 4px;
    }

    textarea {
        padding: 10px 0 10px 5px;
        resize: none;
        width: 100%;
        border: none;
        box-shadow: gray 0px 0px 4px;
    }

    button {
        background-color: var(--primary-color);
        border: none;
        width: 130px;
        color: var(--third-color);
        font-weight: bold;
        padding: 1%;
        margin: 20px auto;
    }
</style>
