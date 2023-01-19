<script>
    import "../app.css";
    import Icon from '@iconify/svelte';
    import Card from "../components/card.svelte";
    import Footer from "../components/footer.svelte";
</script>
  
<nav class="skills flex justify-center bg-red-200 gap-4 p-2">
    <a href="/elixir"><Icon class="elixir-logo h-12 w-12 hover:scale-95 active:scale-90" icon="skill-icons:elixir-dark"/></a>
    <a href="/phoenix" ><Icon class="phoenix-logo h-12 w-12 bg-white hover:scale-95 active:scale-90 rounded-lg" icon="logos:phoenix"/></a>
    <a href="/rust"><Icon class="rust-logo h-12 w-12 hover:scale-95 active:scale-90" icon="skill-icons:rust" /></a>
    <a href="/aws"><Icon  class="aws-logo h-12 w-12 hover:scale-95 active:scale-90" icon="skill-icons:aws-dark"/></a>
</nav>
  
<slot/>

<Footer/>
