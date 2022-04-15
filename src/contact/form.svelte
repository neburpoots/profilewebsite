
<div id="contact" class="spacing container">
    <section class="form">
        <section class="widgets">
            <div class="singlewidget">
                <p class="projecth3">Telefoon</p>
                <a href="tel:0624283290" class="">
                    <div class="widgetflex">
                        <img src="images/vectors/Phonev2.svg" alt="Phone icon" width="50"/>
                        <p class="customwidgetp">0624283290</p>
                    </div>
                </a>
            </div>
            <div class="singlewidget">
                <p class="projecth3">Mail</p>
                <a href="mailto:neburpoots@gmail.com" class="">
                    <div class="widgetflex">
                        <img src="images/vectors/Mail.svg" alt="Phone icon" width="50"/>
                        <p class="customwidgetp">neburpoots@gmail.com</p>
                    </div>
                </a>
            </div>
        </section>
        <div class="formcontainer">
            <h2>Contact</h2>
            <form class="contactform" action="https://api.staticforms.xyz/submit" method="post">
                <input type="hidden" name="accessKey" value="1e8779f8-c6a1-4e69-9f55-4cbd2df2cdfb"> <!-- Required -->
                <div class="name inputlabel">
                    <label class="formlabels" for="name">Naam</label>
                    <input required type="text" id="name" name="name" placeholder="Uw naam">
                </div>

                <div class="email inputlabel">
                    <label class="formlabels" for="email">E-mail</label>
                    <input required type="text" id="email" name="email" placeholder="Uw e-mail">

                </div>

                <div class="subject inputlabel">
                    <label class="formlabels" for="subject">Onderwerp</label>
                    <input required type="text" id="subject" name="subject" placeholder="Onderwerp">

                </div>

                <div class="message inputlabel">
                    <label class="formlabels" for="message">Bericht</label>
                    <textarea required id="message" name="message" placeholder="Uw bericht" style="height:200px"></textarea> 

                </div>
                <input type="hidden" name="redirectTo" value="https://rubenstoop.com?success=1"> 
                <input type="text" name="honeypot" style="display: none;"> 
                {#if success}
                <p><small style="color: green"> Bericht verstuurd! </small></p>
                {/if}  
                <button class="submitbutton" type="submit">Verstuur bericht</button>
            
              </form>
        </div>
    </section>
</div>

<script>
	import { onMount } from 'svelte';

    let success;
    onMount(async () => {
        const link = window.location.href;
        let url = new URL(link);

        let s = url.searchParams.get("success");
        if(s)
        {
            success = true;
        }
    });
</script>


<style>
    .submitbutton {
        background: #A218DB;
        padding: 10px 0 10px;
        border: 0px;
        color: white;
        font-size: 19px;
        border-radius: 40px;
        cursor: pointer;
        margin: 10px 0px 10px 0px;
        width: 200px;
    }
    
    .formcontainer {
        width: 50%;
    }

    .message {
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-start: 3;
        grid-row-end: 4;
    }

    .subject {
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-start: 2;
        grid-row-end: 3;
    }

    .name {
        grid-column-start: 1;
        grid-column-end: 2;
        grid-row-start: 1;
        grid-row-end: 2;
    }

    .email {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 1;
        grid-row-end: 2;
    }

    input {
        width: 100%;
        box-sizing: border-box;
        padding: 10px 20px 10px 20px;
        border-radius: 40px;
        font-size: 15px;
        border: 0px;
        background: #2b2b2b;
        color: white;
    }
    textarea {
        width: 100%;
        box-sizing: border-box;
        width: 100%;
        height: 150px;
        padding: 10px 20px 10px 20px;
        box-sizing: border-box;
        border: 0px;
        border-radius: 20px;
        background-color: #2b2b2b;
        color: white;
        resize: none;
        font-family: 'Manrope', sans-serif;
        font-size: 15px;
    }

    ::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
        color: lightgray;
        opacity: 1; /* Firefox */
    }

    .singlewidget {
        margin-top: 30px;
        margin-bottom: 30px;
    }
    .contactform {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 20px;
        grid-auto-rows: minmax(min-content, max-content);
    }

    .projecth3 {
        margin-bottom: 10px;
    }

    .widgets {
        min-width: 50%;
        align-self: center;
    }

    .customwidgetp {
        color: #A218DB;
        font-size: 32px;
        margin: 10px 0px 0px 20px;
    }

    .widgetflex {
        display: flex;
    }
    .spacing {
        padding-top: 120px;
        padding-bottom: 120px;
        
    }
    .form {  
        padding: 20px;
        background: #121212;
        display: flex;
        flex: 50%;
    }
    h2 {
        margin-top: 0px;
        color: white;
        margin-bottom: 10px;
    }
</style>