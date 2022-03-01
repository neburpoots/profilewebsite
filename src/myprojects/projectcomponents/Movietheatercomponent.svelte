<div class="projects movietheatherapplicatie">

        <article>
            <header>
                <h3 class="projecth3">Bioscoop applicatie</h3>
            </header>
            <main>
                <p class="projectp">
                    Dit is een applicatie voor een bioscoop gemaakt met JavaFX.
                    Dit is voor mij vooral een applicatie geweest om kennis te maken met Java.
                    De applicatie heeft twee bioscoop zalen.
                    Uw kunt met deze applicatie films en shows toevoegen.
                    Uw kan ook tickets verkopen en uitdraaien.
                    Deze applicatie is zo gemaakt dat deze geen database nodig heeft.
                </p>
            </main>
            <footer class="footerflex">
                <a target="_blank" href="https://github.com/neburpoots/javafxmovieTheater/tree/newmaster" >
                    <p class="customlink">Bekijk de applicatie</p>
                </a>
            </footer>
        </article>
        <figure class="gridfigure">
            <a target="_blank" href="images/java1.webp">
                <img class="gridimage" src="images/java1.webp" alt="Afbeelding van de biscoop applicatie">
            </a>
        </figure>


</div>


<style>
    article {
        display: flex;
        flex-direction: column;
        margin-right: 20px;
    }

    .footerflex {
        padding-top: 20px;
    }

    .customlink {
        margin: 0;
    }


    .gridfigure {
        max-width: 100%;
        min-width: 50%;
        margin: 0px;
    }

    .gridimage {
        max-width: 100%;
        min-width: 50%;
    }

    .movietheatherapplicatie {
        display: flex;
        flex-basis: 50%;
        flex-grow: 0;
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-start: 2;
        grid-row-end: 3;
    }

    
</style>