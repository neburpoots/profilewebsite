<script>
    import Client from "./skillcomponents/bottom/Client.svelte";
    import Other from "./skillcomponents/bottom/Other.svelte";

    import Backend from "./skillcomponents/middle/Backend.svelte";
    import Design from "./skillcomponents/middle/Design.svelte";
    import OS from "./skillcomponents/middle/OS.svelte";
    import Frameworks from "./skillcomponents/middle/Frameworks.svelte";
    
    import Diplomas from "./skillcomponents/top/Diplomas.svelte";
    import Experience from "./skillcomponents/top/Experience.svelte";

</script>
<article id="skills" class="container">
    <header>
        <h2>Vaardigheden</h2>
    </header>
    <main>
        <div class="flex top">
            <Diplomas />
            <Experience />
        </div>

        <div class="flex middle">
            <Backend />
            <Design />
            <OS />
            <Frameworks />
        </div>

        <div class="flex bottom">
            <Other />
            <Client />
        </div>
    </main>
</article>

<style>
.flex {
    display: flex;
}
.middle {
    margin-bottom: 100px;
}

.top {
    margin-bottom: 100px;
}

.bottom {
    margin-bottom: 50px;
    max-width: 50%;
}
</style>