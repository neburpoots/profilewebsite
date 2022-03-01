<div class="projects chapoocomponent">
    <figure class="gridfigure">
        <a target="_blank" href="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1646142675/profilewebsite/chapoo1_x19j7i.webp" ><img class="gridimage" src="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1646142675/profilewebsite/chapoo1_x19j7i.webp" alt="Afbeelding van de chapoo applicatie"></a>
    </figure>
    <article class="projecttext">
        <header>
            <h3 class="projecth3">Chapoo</h3>
        </header>
        <main>
            <p class="projectp">
                Chapoo is een applicatie voor een klein fictief restaurant gelegen in Zeewolde.
                De applicatie bevat mogelijkheden om te reserveren en te bestellen. 
                Deze applicatie is gemaakt met C# in Winforms.
                De applicatie update zichzelf async om zo altijd up-to-date te zijn.
                Deze data wordt gehaald uit een SQL database.
            </p>
        </main>
        <footer>
        </footer>
    </article>
    <div class="projectcta">
        <a href="/assets/Chapoo.zip" download ><p class="customlink">Bekijk de applicatie</p></a>
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
    
    .chapoocomponent {
        display: flex;
        flex-direction: column;
        grid-column-start: 1;
        grid-column-end: 2;
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