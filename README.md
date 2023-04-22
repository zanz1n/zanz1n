<style>
    * {
        box-sizing: border-box;
    }

    .images {
        display: flex;
        width: 100%;
        gap: 16px;
        flex-direction: row;
        align-items: center;
        justify-self: center;
    }

    .bigText {
        font-size: 2rem;
        font-weight: bolder;
    }

    .images .score {
        width: 56%
    }

    .images .langs {
        width: 42%;
    }

    @media screen and (max-width: 632px) {
        .images {
            flex-direction: column;
        }

        .images .langs,
        .images .score {
            width: 100%;
        }
    }
</style>

<p class="bigText" align="center">Hi there 👋</p>

<br>

<p class="images">
    <img class="score" src="https://github-readme-stats.vercel.app/api?username=zanz1n&show_icons=true&theme=dracula">
    <img class="langs"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=zanz1n&layout=compact&theme=dracula">
</p>