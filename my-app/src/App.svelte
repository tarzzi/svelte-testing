<script>
    import logo from './assets/svelte.png'
    import Title from './lib/Title.svelte'
    import Sidebar from './lib/Sidebar.svelte';
    import Content from './lib/Content.svelte';
</script>

<main>
  <Sidebar />
  <Content />
  
</main>

<style>
    :root {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
            Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    :global(body){ margin: 0;padding:0;}


</style>
