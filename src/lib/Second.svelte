<section id="section">
    <h2 class="text-4xl mt-15">Te animas a probar nuestra comida vegana?</h2>
    <div>
        <button class="c-button c-button--gooey"> <a href="https://instagram.com/breathe.mendoza?igshid=YmMyMTA2M2Y=">Sí!</a>
            <div class="c-button__blobs">
            <div></div>
            <div></div>
            <div></div>
            </div>
          </button>
    </div>
</section>

<style>
    section{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;

        height: 90vh;
        width: 100%;
        padding: 20vh 0 20vh 0;

        color: white;
        background-color: #5ac4c3;
    }

    h2{
        padding: 10%;
        text-align: center;
    }

    button{
        padding: 10%;
    }
    button:hover{
        color: white;
        background-color: aqua;
    }

    .c-button {
        color: #000;
        font-weight: 700;
        font-size: 16px;
        text-decoration: none;
        padding: 0.9em 1.6em;
        cursor: pointer;
        display: inline-block;
        vertical-align: middle;
        position: relative;
        z-index: 1;
        }

        .c-button--gooey {
        color: #abf1ff;
        text-transform: uppercase;
        letter-spacing: 2px;
        border: 4px solid #abf1ff;
        border-radius: 0;
        position: relative;
        transition: all 700ms ease;
        }

        .c-button--gooey .c-button__blobs {
        height: 100%;
        filter: url(#goo);
        overflow: hidden;
        position: absolute;
        top: 0;
        left: 0;
        bottom: -3px;
        right: -1px;
        z-index: -1;
        }

        .c-button--gooey .c-button__blobs div {
        background-color: #abf1ff;
        width: 34%;
        height: 100%;
        border-radius: 100%;
        position: absolute;
        transform: scale(1.4) translateY(125%) translateZ(0);
        transition: all 700ms ease;
        }

        .c-button--gooey .c-button__blobs div:nth-child(1) {
        left: -5%;
        }

        .c-button--gooey .c-button__blobs div:nth-child(2) {
        left: 30%;
        transition-delay: 60ms;
        }

        .c-button--gooey .c-button__blobs div:nth-child(3) {
        left: 66%;
        transition-delay: 25ms;
        }

        .c-button--gooey:hover {
            color: #5ac4c3;
        }

        .c-button--gooey:hover .c-button__blobs div {
        transform: scale(1.4) translateY(0) translateZ(0);
        }
</style>