<div class="projects gpucomponent">
    <figure class="gridfigure">
        <a target="_blank" href="images/videocard2.webp" ><img class="gridimage" src="images/videocard2.webp" alt="Afbeelding van de videokaarten webshop"></a>
    </figure>
    <article class="projecttext">
        <header>
            <h3 class="projecth3">Videokaarten webshop</h3>
        </header>
        <main>
            <p class="projectp">
                De videokaarten webshop is een webshop die ik voor het vak webdevelop moest maken. 
                Deze webshop is gemaakt met plain PHP  en Javascript. 
                We mochten namelijk voor dit project geen gebruik maken van Libraries/Frameworks. 
                De enige uitzondering hiervoor is bootstrap. 
                Dit heb ik gebruikt om het er redelijk snel netjes uit te laten zien. 
                Dit is echter zeker geen project waar ik trots op ben vanwege de looks. 
            </p>
        </main>
        <footer>
        </footer>
    </article>
    <div class="projectcta">
        <a target="_blank" href="https://rubenstoop.com" ><p class="customlink">Bekijk de website</p></a>
    </div>
</div>

<style>
    a {
        display: inline-flex;
        
    }

    .projectcta {
        padding-top: 20px;
    }

    .customlink {
        margin: 0;
    }

    .projecth3 {
        margin-top: 20px;
    }
    
    .gpucomponent {
        display: flex;
        flex-direction: column;
        grid-column-start: 3;
        grid-column-end: 4;
        grid-row-start: 2;
        grid-row-end: 4;
    }

    .gridfigure {
        max-width: 100%;
        margin: 0px;
    }

    .gridimage {
        max-width: 100%;
    }
</style>