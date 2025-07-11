<script lang="ts">
    export let parametro: number;
    import { LibraryBig } from 'lucide-svelte';
</script>

<header>
    <div>
        <LibraryBig strokeWidth={1.25} />
    </div>

    <div>
        <a>teste.com</a>
    </div>

    <div>
        <p>right</p>
    </div>

    <!--<a href="https://www.vecteezy.com/free-vector/book">Book Vectors by Vecteezy</a>-->
</header>

<style>
    header {
        height: 100%;
        display: flex;
        background: #4584FF;    
    }

    @media (max-height: 500px) {
        header {
            height: 20vh;
        }
    }
    
</style>