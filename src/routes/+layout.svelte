<header>
    <div id="LogoAndText">
    <img src="/logo.png" alt="">    

    <div id="TitleAndText">
    <h1 id="Title">Neurodivergent <br> Narratives</h1>
    <h2 id="HeadingText">A safe space for everyone</h2>
    </div>
    </div>
    <nav>
        <a href="/">Home</a>
        <a href="">Blog</a>
        <a href="">Resources</a>
    </nav>
</header>

<main>
    <slot/>
</main>

<style>
    img {
        height: 45vmin;
    }
    header {
        display: flex;
        flex-direction: column;
        border: 1vmin solid;
        border-image: linear-gradient(to right,#ED008C, #9D1E63, #E1423C, #F8931D, #FBC654, #FFDB6B) 20;
        padding: 2vmin;
        margin-bottom: 2vmin;
    }
    #LogoAndText {
        display: flex;
        flex-direction: row;
    }
    #TitleAndText {
        width: 100%;
        margin: auto;
    }
    #Title {
        text-align: center;
        font-size: 11vmin;
        margin: 4vmin;
    }
    #HeadingText {
        text-align: center;
        font-size: 4.5vmin;
        font-weight: lighter;
    }
    nav {
        text-align: center;
    }
    a {
        margin: 2vmin 2vmin auto 2vmin;
        font-size: 2.5vmin;
        padding: 1vmin;
        text-decoration: none;
    }
    a:hover {
        border: .40vmin solid;
        border-image: linear-gradient(to right,#ED008C, #9D1E63, #E1423C, #F8931D, #FBC654, #FFDB6B) 1;
        color: black;
    }
    :global(h3) {
    font-size: 4.5vmin;
    }
    main {
        margin: 3vmin;
    }
</style>