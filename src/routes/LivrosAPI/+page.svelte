<script lang="ts">
	import { onMount } from "svelte";
    //repetir esses passos agora com o usuário

    let livros:{createdAt:string, Titulo:string, Autor:string, Descricao:string}[] = $state([]);

    //funçao assincrona é uma função que funciona em segundo plano.
    async function load() {
        //cria uma variavel com a funçao fetch(), usando o link dos objetos do mockApi.
        try {
            const resposta = await fetch("https://6895f776039a1a2b2890fb87.mockapi.io/api/v1/Livro")
            const livros = await resposta.json();
            return livros;
        } catch(error) {
            console.error("Erro ao buscar livros", error);
        }
    }

    //"on mount" durante o carregamento da página (tipo onload).
    onMount(async () => {
        livros = await load();
    })
</script>

    {#each livros as livro}
        <div style="border: 1px solid lightgrey; margin:3px; padding: 10px; border-radius: 10px; box-shadow: inset -3px -3px 10px lightgrey">
        <h1>{livro.Titulo}</h1>
        <p>{livro.Autor}</p>
        <p>{livro.Descricao}</p>
        </div>
    {/each}