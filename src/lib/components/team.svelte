<div class="container">
    <div>
        <h2>Dev Team</h2>

        <div class="cont">
            <div class="card">
                <img src="minegame.jpg" loading="lazy" alt="MineGame159">
                <p><b>MineGame159</b></p>
                <span>Owner / Head Developer</span>
            </div>
            <div class="card">
                <img src="seasnail.jpg" loading="lazy" alt="seasnail">
                <p><b>seasnail</b></p>
                <span>Developer</span>
            </div>
        </div>

        <div class="cont">
            <a href="/discord" target="_blank" class="button" style="background-color: var(--discord);"><img src="icons/discord.svg" loading="lazy" alt="discord">Discord</a>
            <a href="/github" target="_blank"  class="button" style="background-color: var(--github);"><img src="icons/github.svg" loading="lazy" alt="github">GitHub</a>
            <a href="/youtube" target="_blank"  class="button" style="background-color: var(--youtube);"><img src="icons/youtube.svg" loading="lazy" alt="youtube">YouTube</a>
            <a href="/donate" target="_blank"  class="button" style="background-color: var(--paypal);"><img src="icons/paypal.svg" loading="lazy" alt="donate">Donate</a>
        </div>
    </div>
</div>

<style>
    .cont {
        display: flex;
        justify-content: center;
        gap: 3rem;
        padding-top: 3rem;
    }

    .card {
        box-shadow: 0 0 16px rgba(0, 0, 0, 0.25);
        padding: 1rem;
        transition: box-shadow 0.25s;
        border-radius: 0.375rem;
        padding: 2rem;
    }

    .card:hover {
        box-shadow: 0 0 16px rgba(0, 0, 0, 0.4);
    }

    .card img {
        border-radius: 50%;
        width: 14rem;
        margin-bottom: 1.5rem;
    }

    a {
        background-image: none;
    }

    @media screen and (max-width: 1100px) {
        .cont {
            flex-direction: column;
            gap: 1.5rem;
        }
    }

    @media screen and (max-width: 300px) {
        .card img {
            width: 10rem;
        }
    }
</style>
