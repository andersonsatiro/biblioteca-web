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
        }
    ]
</script>

<main>
        <!-- menu scroll -->
        <section class="menu-scroll"> 
            <p>TITULO SEÇÃO</p>
            <ul class="scroll">
                {#each lista as livro}
                <li>
                    <a href=""><img class="scroll-capa-livro" width="150px" src={livro.imagem} alt={livro.titulo}></a>
                    <div class="scroll-capa-informacao">
                        <a href="">{livro.titulo}</a>
                        <a href="">{livro.autor}</a>
                    </div>
                </li>
                {/each}
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

    .scroll li {
        min-width: fit-content;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0 16px;
        padding-top: 30px;

        img {
            width: 140px;
            height: 200px;
            border-radius: 10px;
        }
    }

    .scroll {
        border: 1px solid whitesmoke;
        background-color: white;
        box-shadow: inset 0 0 20px rgb(244, 244, 244);
        border-radius: 30px;
        width: 80vw;
        overflow: scroll;
        display: flex;
        overflow-x: auto;
        padding: 0;
        margin: 0;
        list-style-type: none;
    }

    .scroll-capa-informacao * {
        display: flex;
        width: fit-content;
        margin: auto;
    }
            
    ::-webkit-scrollbar {
        width: 0px;
    }

</style>