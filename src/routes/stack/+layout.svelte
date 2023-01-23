<script>

</script>

<section class='flex flex-col  justify-start mx-4 h-full '>

    <h1 class='text-2xl text-white font-black tracking-widest'>The Stack.</h1>
    <div class='flex'>
        
        <aside class=' flex flex-col h-96 gap-2 items-start justify-start'>
            
            <button class='btn'>
                <a href="/stack/elixir">elixir</a>
            </button>
            <button class='btn'>
                <a href="/stack/phoenix">phoenix</a>
            </button>
            <button class='btn'>
                <a href="/stack/rust">rust</a>
            </button>
            <button class='btn'>
                <a href="/stack/aws">aws</a>
            </button>
            
            
        </aside>
        <div class='w-full description text-center'>
            <slot/>
        </div>
        

    </div>

</section>