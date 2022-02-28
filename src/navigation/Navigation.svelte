<script>
    function menuOnClick() {
        document.getElementById("menu-bar").classList.toggle("change");
        document.getElementById("nav").classList.toggle("change");
        document.getElementById("menu").classList.toggle("change-bg");
    }
</script>

<div id="menu">
        <div
            id="menu-bar"
            on:click={() => (menuOnClick())}
        >
            <div id="bar1" class="bar" />
            <div id="bar2" class="bar" />
            <div id="bar3" class="bar" />
    </div>
    <div id="nav" class="nav">
        <ul>
            <nav>
                <a href="#profilecard"><p>Over mij</p></a>
                <a href="#skills"><p>Mijn vaardigheden</p></a>
                <a href="#projects"><p>Projecten</p></a>
                <a href="#contact"><p>Contact</p></a>
            </nav>
        </ul>
    </div>

</div>

<div class="menu-bg" id="menu-bg" />

<style>
#menu-bar {
    display: grid;
    grid-gap: 5px;
}

</style>