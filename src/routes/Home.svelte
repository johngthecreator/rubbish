<script>

</script>
<main>
    <img src="./atom.webp" alt="geometric atom" />
    <div class="introText">
        <h2>file sharing. <br> decrentralized.</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Nunc faucibus a pellentesque sit. Diam phasellus vestibulum lorem sed risus ultricies tristique nulla. Ac ut consequat semper viverra nam. Orci phasellus egestas tellus rutrum tellus pellentesque. Quisque non tellus orci ac auctor augue mauris augue neque.</p>
    <button>Get Started</button>
    </div>
</main>
<style>
    .rotate {
    }

    @keyframes rotation {
        from {
            transform: rotate(0deg);
        }
        to {
            transform: rotate(360deg);
        }
    }
    main {
        display: flex;
        flex-direction: row;
        justify-content: center;
    }
    button {
        font-size: 20px; 
        font-weight: 700; 
        background-color: #303030;
        color: white;
        display: flex;
        align-items: center;
        border: 2px solid white;
        border-radius: 5px;
        padding: 5px 15px;
        width: auto;
    }
    h2,p {
        color: white;
    }
    div.introText {
        padding: 15px;
        max-width: 600px;
    }
    img {
        width: 100%;
        max-width: 500px;
        aspect-ratio : 1 / 1;
        animation: rotation 45s infinite linear;
    }
    @media screen and (max-width: 820px){
        main{
            display: flex;
            flex-direction: column;
            align-items: center;
        }

    }
</style>