<script>
import ChapooComponent from "./projectcomponents/ChapooComponent.svelte";

import GpuComponent from "./projectcomponents/GpuComponent.svelte";

import Movietheathercomponent from "./projectcomponents/Movietheatercomponent.svelte";
import NoSqlComponent from "./projectcomponents/NoSQLComponent.svelte";
import SomerenComponent from "./projectcomponents/SomerenComponent.svelte";
import VineyardComponent from "./projectcomponents/VineyardComponent.svelte";

</script>

<div id="projects" class="container flexmiddle">
    <div class="gridcontainer">
        <article class="projects projectcomponent">
            <header>
                <h2>Projecten</h2>
            </header>
            <main>
                <p>
                    Hieronder vindt u projecten welke ik zelf heb gemaakt of een significante bijdrage aan heb geleverd.  Een deel van de projecten staan op mijn eigen Git. Er zijn ook projecten die op de git van een teamlid staan waarmee ik heb samengewerkt. Let op! Sommige van deze projecten hebben een database nodig.
                </p>
            </main>
        </article>
        <Movietheathercomponent />
        <GpuComponent />
        <ChapooComponent />
        <SomerenComponent />
        <VineyardComponent />
        <NoSqlComponent />
    </div>
</div>


<style>
    .projectcomponent {
        grid-column-start: 1;
        grid-column-end: 4;
        grid-row-start: 1;
        grid-row-end: 1;
    }

    .gridcontainer {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap: 20px;
        grid-auto-rows: minmax(min-content, max-content);
    }
    
    .flexmiddle {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    h2 {
        color: white;
    }

</style>