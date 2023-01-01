<script>
    import "../styles/global.css";
</script>

<header>
    <nav>
        <ul>
            <li><a href="/"><img src="logo-long.svg" alt="LOGO"></a></li>
            <li><a href="/about">about</a></li>
            <li><a href="/services">services</a></li>
            <li><a href="/gallery">gallery</a></li>
        </ul>
        <button href="/contact">contact us!<img src="send.svg" alt=""></button>
    </nav>
</header>

<style>
    nav {
        height: 124px;
        background-color: #F7F5F3;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0px 48px;
        box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
    }

    ul {
        height: 100%;
        display: flex;
        justify-content: flex-start;
        gap: 64px;
        align-items: center;

    }
    li {
        list-style: none;
    }
    li a {
        text-decoration: none;
        color: black;
        font-family: 'Outfit', sans-serif;
        font-size: 20px;
        font-weight: 300;

    }
    button {
        /* position */
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 18px 36px;
        box-sizing: border-box;
        border-radius: 50px;
        width: 200px;
        height: 48px;

        /* colour */
        color: white;
        background: #6756DE;
        border: 1px solid #967EFF;
        
        white-space: nowrap;
        isolation: isolate;
        
        /* font */
        font-weight: 400;
        font-family: 'Outfit', sans-serif;
        font-size: 20px;
    }

    button:hover {
        background: #5043BA;
    }

</style>