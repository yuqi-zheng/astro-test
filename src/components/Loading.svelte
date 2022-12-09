<script>
    import { Jellyfish } from 'svelte-loading-spinners';
</script>

<div id="loader">
    <Jellyfish size="60" color="#77CCFF" unit="px" duration="2s"/>
    <h1>DEVELOPMENT IN PROGRESS</h1>
</div>

<style>
    #loader {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        position: fixed;
        top: 40%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    h1 {
        font-family: 'Archivo Black', sans-serif;
        text-align: center;
    }
</style>