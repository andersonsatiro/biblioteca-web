<script lang="ts">
  import { Instagram, Github, Twitter } from 'lucide-svelte';
</script>

<footer>
    <section>
        <h2>Assine nossa Newsletter</h2>
        
        <form>
            <input>
            <button>Clique aqui</button>
        </form>
    </section>

    <div>
        <div>
            <nav>
                <ul>
                    <li>Sobre</li>
                    <li>Sobre</li>
                    <li>Sobre</li>
                    <li>Sobre</li>
                </ul>
            </nav>

            <div>
                <Instagram size={32}/>
                <Github size={32} />
                <Twitter size={32} />
            </div>
        </div>

        <hr />

        <div>
            <p>Biblioteca Web</p>
        </div>
    </div>
</footer>

<style>
    footer {
        display: flex;
        background: rgb(255, 255, 150);
    }
</style>