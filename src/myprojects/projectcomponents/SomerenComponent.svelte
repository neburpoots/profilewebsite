<div class="projects somerencomponent">
    <figure class="gridfigure">
        <a target="_blank" href="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1650019601/vueapp_dv0vcy.webp" ><img class="gridimage" src="https://res.cloudinary.com/dg5wrkfe7/image/upload/v1650019601/vueapp_dv0vcy.webp" alt="Afbeelding van de someren applicatie"></a>
    </figure>
    <article class="projecttext">
        <header>
            <h3 class="projecth3">Videokaarten webshop V2</h3>
        </header>
        <main>
            <p class="projectp">
                De videokaarten webshop v2 is gemaakt voor het vak webdevelopment 2. 
                Voor deze webshop heb ik Vue 3 bij de client-app gebruikt. 
                De back-end API is met Laravel gemaakt. 
                Deze applicatie maakt gebruik van JWT tokens, Vuex en axios.
            </p>
        </main>
        <footer>
        </footer>
    </article>
    <div class="projectcta">
        <a target="_blank" href="https://github.com/neburpoots/Videocardwebshop-laravel-API" ><p class="customlink">Bekijk de applicatie</p></a>
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