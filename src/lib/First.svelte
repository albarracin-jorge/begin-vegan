<script>
    import icon from '../assets/icon.jpeg';
</script>

<section>
    <img src={icon} alt="">
    <h1 class="text-4xl mt-7 mb-7">Te esperamos!</h1>
    <a href="#section">
        <div class="container_mouse">
            <span class="mouse-btn">
                <span class="mouse-scroll"></span>
            </span>
        </div>
    </a>

    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#5ac4c3" fill-opacity="1" d="M0,96L48,117.3C96,139,192,181,288,181.3C384,181,480,139,576,144C672,149,768,203,864,218.7C960,235,1056,213,1152,192C1248,171,1344,149,1392,138.7L1440,128L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
</section>

<style>
    section{
        display: flex;
        flex-direction: column;
        /* justify-content: space-around; */
        align-items: center;
        height: 85vh;
    }
    .mouse-btn {
        margin: 10px auto;
        width: 40px;
        height: 80px;
        border: 3px solid rgba(143, 208, 217, 0.918);
        border-radius: 20px;
        display: flex;

        position: absolute;
        z-index: 1;

        background-color: white;
    }

    .mouse-scroll {
        display: block;
        width: 20px;
        height: 20px;
        background: linear-gradient(170deg, rgba(143, 208, 217, 0.918), rgb(143, 208, 217));
        border-radius: 50%;
        margin: auto;
        animation: scrolling13 1s linear infinite;
    }

    @keyframes scrolling13 {
    0% {
        opacity: 0;
        transform: translateY(-20px);
    }

    100% {
        opacity: 1;
        transform: translateY(20px);
    }
    }

    svg{
        position: absolute;
        bottom: 0;
    }
</style>