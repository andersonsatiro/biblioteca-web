<script lang="ts">
    let lista = [
        {
            id: 0,
            titulo: "Rainha Vermelha",
            autor: "Victoria Aveyard",
            genero:["distopia", "romance"],
            imagem: "https://i.pinimg.com/736x/15/98/35/159835be5f620947bb9146a316accd8c.jpg"
        },
        {
            id: 1,
            titulo: "Estilhaça-me",
            autor: "Tahereh Mafi",
            genero:["distopia"],
            imagem: "https://i.pinimg.com/1200x/f1/6e/4b/f16e4bb781964a4e32bf50620ac2dc55.jpg"
        },
        {
            id: 2,
            titulo: "Pessoas Normais",
            genero:["romance"],
            autor: "Sally Rooney",
            imagem: "https://i.pinimg.com/736x/89/30/1b/89301b3844880e80b117e27065b74478.jpg"
        },
        {
            id: 3,
            titulo: "Admirável Mundo Novo",
            genero:["distopia", "romance"],
            autor: "Aldous Huxley",
            imagem: "https://i.pinimg.com/1200x/9d/73/6c/9d736c2ea62e9e8abe062c2a5059d17c.jpg"
        },
        {
            id: 3,
            titulo: "Admirável Mundo Novo",
            genero:["distopia", "romance"],
            autor: "Aldous Huxley",
        }
    ]
</script>

<main >
        <!-- menu scroll -->
        <section> 
            <p>Titulo do menu scroll</p>
            <ul class="menu-scroll"></ul>
                {#each lista as livro}
                <img width="150px" src="livro.imagem" alt="livro.titulo">
                {/each}
        </section>

        <section>
            <p>Titulo do menu scroll</p>
            <ul class="menu-scroll">
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/93/5a/68/935a68b042d6b5233cb048b15714bb53.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
            </ul>
        </section>

        <section>
            <p>Titulo do menu scroll</p>
            <ul class="menu-scroll">
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
                <li>
                    <img class="livro-capa" src="https://i.pinimg.com/736x/88/91/2c/88912cd973df21c2ba1d72c258eb080b.jpg" alt="">
                    <p class="livro-titulo">Título do Livro</p>
                    <p class="livro-autor">Autor do Livro</p>
                </li>
            </ul>
        </section>
    </main>

<style>
    main {
        display: block;
        margin: auto;
        background-color: white;
        height:100vh;
        width: 80vw;
    }

    .menu-scroll li {
        min-width: fit-content;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0 16px;
    }

    .menu-scroll {
        width: 80vw;
        overflow: scroll;
        display: flex;
        overflow-x: auto;
        padding: 0;
        margin: 0;
        list-style-type: none;
    }

    .livro-capa {
        height: 160px;
        width: 100px;
        object-fit: cover;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        margin-bottom: 8px;
    }
</style>