<script>

</script>

<section class='flex flex-col p-6 justify-start mx-4 h-full drop-shadow-2xl shadow-2xl bg-blue-300'>

    <h1 class='text-2xl'>The Stack</h1>
    <div class='flex'>
        
        <aside class='w-1/4 flex flex-col bg-red-400'>
            
            <a href="/stack/elixir">elixir</a>
            <a href="/stack/phoenix">phoenix</a>
            <a href="/stack/rust">rust</a>
            <a href="/stack/aws">aws</a>
            
        </aside>
        <div class='w-full description text-center'>
            <slot/>
        </div>
        

    </div>

</section>