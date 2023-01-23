<script>
    import "../app.css";
    import Icon from '@iconify/svelte';
    import Card from "../components/card.svelte";
    
    
    import Header from '../components/header.svelte'
    import Button from '../components/button.svelte'


    
</script>
  
<div class="flex flex-col h-screen justify-between">
    <Header addClass='h-10 bg-red-500'/>
    <nav class='flex gap-4  self-center justify-center mt-12'>

        <button>
            <a href='/stack'>The Stack</a>
        </button>
        <button>
            <a href='/certifications'>Certifications</a>
        </button>
        <button>
            <a href='/me'>About Me</a>
        </button>
        
    </nav>
    <main class='h-full my-4'>
        <slot/>
    </main>
    
</div>

