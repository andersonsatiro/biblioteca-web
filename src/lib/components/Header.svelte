<script lang="ts">
    export let parametro: number;
    import { Heart, Settings, UserRound } from 'lucide-svelte';
</script>
    
<header class="flex items-center justify-between px-9 py-7 mb-5">
    <h2 class="text-3xl font-bold">LitCloud</h2>

    <nav>
        <ul class="flex items-center gap-8 text-gray-900">
            <li>Destaques</li>
            <li>Acervo</li>
            <li>Mais vendidos</li>
            <li>Solicitar</li>
            <li>Sobre</li>
            <li>Contato</li>
        </ul>
    </nav>

    <div class="flex items-center gap-4">
        <div class="wrapper-icon">
            <Heart size={18} color="#596780" />
        </div>

        <div class="wrapper-icon">
            <Settings size={18} color="#596780" />
        </div>

        <div class="wrapper-icon">
            <UserRound size={18} color="#596780" />
        </div>
    </div>
</header>

<style>
    header {
        border-bottom: 1px solid rgba(195, 212, 233, 0.4);
    }

    h2 {
        color: #3563E9;
    }

    .wrapper-icon {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 3.2rem;
        width: 3.2rem;
        border-radius: 100%;
        border: 1px solid rgba(195, 212, 233, 0.4);
    }

    .wrapper-icon:hover {
        cursor: pointer;
        color: white;
        background-color: #3563E9;
    }
</style>