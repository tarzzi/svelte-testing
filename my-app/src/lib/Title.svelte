<script>
    import logo from '../assets/svelte.png'
</script>

<div class="title">
    <img src={logo} alt="Svelte Logo" />
    <h1>velte tasks</h1>
</div>

<style>
    img {
        width: 40px;
    }
    h1 {
        display: inline;
        margin-left: -3px;
    }
    .title {
        display: flex;
        justify-items: center;
        justify-content: center;
        align-items: center;
    }
</style>
