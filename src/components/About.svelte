<script>
    import Bear from "../assets/Bear.svg"
    

</script>

<section>
    <div class="container_about" id="About">
        <img width={180} height={123} src={Bear} alt=" "/>
        <p class="header--small"> Hi, I'm bear</p>
        <p class="header--big">WELCOME TO MY PORTFOLIO</p>
    </div>
</section>

<style>
    .container_about {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 10rem;
    }
    .header--small {
        font-size: 1.5rem;
        margin: 2rem 0 0 0;
        font-weight: 600;
    }
    .header--big {
        font-size: 2rem;
        color: #2C91C6;
        font-weight: 700;

    }
</style>