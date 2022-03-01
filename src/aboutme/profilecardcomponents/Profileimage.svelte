<script>
    let src = "https://res.cloudinary.com/dg5wrkfe7/image/upload/v1646142675/profilewebsite/profilepicv2_sb4dnw.webp";
</script>

<figure>
    <img class="profileimage" src="{src}" alt="Profiel foto">
</figure>

<style>
    figure {
        margin: 0;
        flex-basis: 100%;
        flex-grow: 1;
        text-align:center;
        display: flex;
    }
    img {
        max-height: 100%;
        clip-path: circle();
        margin-left: auto;
        margin-right: auto;
        max-width: 100%;
        object-fit: contain;
    }
</style>