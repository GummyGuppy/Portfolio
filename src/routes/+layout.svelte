<script>
    import "../app.css";
    import Icon from '@iconify/svelte';
    import Card from "../components/card.svelte";
</script>
  
<nav class="skills flex justify-center bg-red-200 gap-4 p-2">
    <a href="/elixir"><Icon class="elixir-logo h-12 w-12" icon="skill-icons:elixir-dark"/></a>
    <a href="/phoenix" ><Icon class="phoenix-logo h-12 w-12" icon="logos:phoenix"/></a>
    <a href="/rust"><Icon class="rust-logo h-12 w-12" icon="vscode-icons:file-type-rust"/></a>
    <a href="/aws"><Icon  class="aws-logo h-12 w-12" icon="logos:aws"/></a>
</nav>
  
<slot/>
<div class="flex flex-col justify-center gap-2 mt-12">
    

    <div class=" flex justify-center items-center h-2
    animate-in slide-in-from-bottom duration-2s tracking-widest">
      CONTACT
    </div>
    <div class="justify-center flex pb-2 gap-2 animate-in slide-in-from-right zoom-in-50 duration-2s ">
  
      <a href="https://github.com/gummyguppy">
        <Icon icon="fa:github-alt" height="32"/>
      </a>
  
      <a href="https://www.linkedin.com/in/earl-born-b959a9227/">
        <Icon icon="logos:linkedin-icon" height="32" />
      </a>
      
  
    </div>
    <div class="flex justify-center items-center h-2
    animate-in slide-in-from-bottom duration-2s tracking-widest">
      THIS SITE CREATED WITH
    </div>
    <div class='justify-center items-center flex flex-col lg:flex-row pb-2 gap-4'>
      <a href="https://kit.svelte.dev/">
        <Icon icon="logos:svelte-kit" height="24" class="hover:drop-shadow-[0_0_2em_#b8a3bb]"/>
      </a>

      <a href="https://https://vercel.com/">
        <Icon icon="logos:vercel" height="24" class="hover:drop-shadow-[0_0_2em_#8A2BE2]"/>
      </a>

      <a href="https://tailwindcss.com/">
        <Icon icon="logos:tailwindcss" height="24" class="hover:drop-shadow-[0_0_2em_#15C2B8]"/>
      </a>
      
    </div>
  
      
      
      
  </div>