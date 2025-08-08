<script lang="ts">
	import { onMount } from "svelte";

    let livros:{titulo:string, autor:string, descricao:string, createdAt:string}[]=$state([])
    async function load() {
        try {
            const resposta = await fetch("https://6895f773039a1a2b2890fb56.mockapi.io/api/v1/livro");
            const livros = await resposta.json();
            return livros;
        }
        catch(error) {
            console.error("Erro ao buscar os livros: ", error);
        }
    }
    onMount(async () => {livros = await load();})
</script>

{#each livros as livro}
    <div class="bg-white shadow-md rounded-lg p-6 mb-4">
        <h1 class="text-xl font-bold mb-2">{livro.titulo}</h1>
        <p class="text-gray-700 mb-1">{livro.autor}</p>
        <p class="text-gray-600 mb-1">{livro.descricao}</p>
        <p class="text-gray-400 text-sm">{livro.createdAt}</p>
    </div>
{/each}