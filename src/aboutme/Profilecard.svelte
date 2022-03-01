<script>
    import Profileimage from "./profilecardcomponents/Profileimage.svelte";
    import Profiletext from "./profilecardcomponents/Profiletext.svelte";
</script>

    <div id="profilecard" class="profilecard">
        <div class="paddingcard">
            <Profileimage />
            <Profiletext />
        </div>
    </div>



<style>

.paddingcard {
    display: flex;
    padding: 40px;
    gap: 20px;
}
    
.profilecard {
    display: flex;
    max-width: 1100px;
    margin-left: auto;
    margin-right: auto;
    background: #121212;
    max-height: 563px;
    -webkit-box-shadow: 0px 0px 97px 30px rgba(0,0,0,0.43);
    -moz-box-shadow: 0px 0px 97px 30px rgba(0,0,0,0.43);
    box-shadow: 0px 0px 97px 30px rgba(0,0,0,0.43);
}
</style>