
<template>
    <div class  = contactBox>

        <div class= contactContainer>


            <div class = text>
            Why not drop me a message and we can have a chat - I don't bite.
            </div>


            <div class = button>
              <a href="mailto:info@owenkempton.com?Subject=Hello!">Let's go!</a>
            </div>
        </div>

    </div>
</template>
<script>

</script>

<style scoped>


.contactBox {
    margin-top: 5vw;
    margin-bottom: 5vw;
}

.contactContainer{
    height: 15vh;
    background-color: rgba(255, 255, 255, 100);
    width: 90vw;
    margin-left: 5vw;
    margin-right: 5vw;
    border-radius: 12px;
    text-align: center;
    }


.contactBox {

}

.button {
    background-color: rgba(240, 255, 255, 100);
    border-radius: 12px;
    width: 400px;
    height: 50px;
    padding-top: 1vh;
    padding-bottom: 1vh;
    float:right;
    margin-top: 6vh;
    margin-right: 5vw;
}

.text {
    padding-top: 6vh;
    padding-left: 5vw;
    float:left;}


 /* Override CSS for smaller displays */
@media only screen and (max-width: 1000px) {
  .contactContainer{
    height: 15vh;
    text-align: center;
    }

    .text {
        padding-top: 3vh;
        float:none;

    }

    .button {
        margin-top: 2vh;
        padding-top: 1vh;
        padding-bottom: 1vh;
        width: 50vw;
        margin-left: 20vw;
        margin-right: 20vw;
        float:none;

    }
}



</style>
