
<script>
    import logo from '../lib/assets/favicon.png'
    import about from '../lib/assets/about.svg'
</script>
<nav>
    <div class="logo"><img class="logo-img" src={logo} alt="Syntax Dev Logo"/></div>
    <!-- <img class="about-img"src={about} alt="building about logo"> -->
    <div class="about"><a href="/about">ABOUT</a></div>
    <div class="showcase"><a href="/showcase">SHOWCASE</a></div>
    <div class="contact"><a href="/contact">CONTACT</a></div>
</nav>
<main>

</main>

<style>
    nav {
        display: flex;
        flex-direction: row;
        text-align: center;
        align-items: center;
        flex-basis: 100px;
        background: rgb(0, 0, 0);
        border-bottom: 2px solid gray;

    }
    main {
        background-image: linear-gradient(to bottom, black, rgb(19, 19, 19));
    }

    nav > div {
        font-size: 16px;
        transition: background 0.3s;
        height: 100%;;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    nav > .about:hover, .contact:hover, .showcase:hover {
        background: rgb(27, 27, 27);
        cursor: pointer;
    }

    nav > .about:active, .contact:active, .showcase:active {
        background: rgb(54, 54, 54);   
    }
    
    nav > .logo {
        justify-content: start;
    }

    nav > div > a {
        color: white;
        text-decoration: none;
    }

    .logo {
        flex-grow: 2;
        text-align: left;
    }
    .logo-img {
        height: 100px;
        width: 100px;
    }
    .about {
        flex-grow: 1;
    }
/* 
    .about-img {
        margin-left: 5px;
        vertical-align: middle;
        height: 16px
    } */

    .showcase {
        flex-grow: 1;
    }
    .contact {
        flex-grow: 1;
    }
    main {
        flex-grow: 1;
    }
</style>

