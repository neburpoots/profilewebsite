<div class="projects somerencomponent">
    <figure class="gridfigure">
        <a target="_blank" href="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1646142675/profilewebsite/someren4_kjy71t.webp" ><img class="gridimage" src="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1646142675/profilewebsite/someren4_kjy71t.webp" alt="Afbeelding van de someren applicatie"></a>
    </figure>
    <article class="projecttext">
        <header>
            <h3 class="projecth3">Someren</h3>
        </header>
        <main>
            <p class="projectp">
                Someren is een applicatie voor een zomerkamp met studenten en leraren.
                Bij het zomerkamp worden allerlei activiteiten gehouden zoals feestjes en sport evenementen.
                De applicatie is in c# met winforms gemaakt.
                Bij deze applicatie ging het vooral om de functionaliteit en niet om de looks.
            </p>
        </main>
        <footer>
        </footer>
    </article>
    <div class="projectcta">
        <a href="/" ><p class="customlink">Bekijk de applicatie</p></a>
    </div>
</div>

<style>
    a {
        display: inline-flex;
    }

    .customlink {
        margin: 0;
    }

    .projecth3 {
        margin-top: 20px;
    }
    
    .somerencomponent {
        display: flex;
        flex-direction: column;
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 3;
        grid-row-end: 5;
    }

    .gridfigure {
        max-width: 100%;
        margin: 0px;
    }

    .gridimage {
        max-width: 100%;
    }
</style>