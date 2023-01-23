<script>
    import "../app.css";
    import Icon from '@iconify/svelte';
    import Card from "../components/card.svelte";    
    import Header from '../components/header.svelte'
    import Button from '../components/button.svelte'
    
</script>
  
<div class="flex flex-col h-screen justify-between bg-cover" style="background-image: url('https://img.freepik.com/premium-photo/rows-shelves-with-goods-boxes-modern-industry-warehouse-store-factory-warehouse-s_61243-279.jpg?w=740')">

    <nav class='flex gap-2 self-center justify-center my-12'>

        <button class='btn font-extrabold'>
            <a href='/stack'>Stack</a>
        </button>
        <button class='btn font-extrabold'>
            <a href='/certifications'>Certifications</a>
        </button>
        <button class='btn font-extrabold'>
            <a href='/me'>About</a>
        </button>
        
    </nav>
    <main class='h-full my-4'>
        <slot/>
    </main>
    
</div>

