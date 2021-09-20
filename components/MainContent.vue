<!-- Main page block -->
<template>
    <div>
        <div class = container>
        
            <div class = title>
                <vue-typed-js :loop="true" :cursorChar="'_'" :startDelay="1000" :strings="['A website', 'An opportunity', 'An inspiration']">
                <h1><span class="typing"></span>... by me</h1>
                </vue-typed-js>
            </div>

            <div class = followUp>
                Coming soon
            </div>

        
        </div>






    </div>



</template>



<script>
import Vue from 'vue'
import VueTypedJs from 'vue-typed-js'
Vue.use(VueTypedJs)
export default {
  created() {
    console.log('Component has been created!');
    loopItems()
    function loopItems(){
        //Loop though items on the page
        let Items = 'hello'
        return Items
    }
  }
};



</script>
<style scoped>
.container {
    /* This is the css for the big box */
    height: 60vh;
    margin-top: 30vh;
    background-color: rgba(0, 0, 0, 0.1);
    padding-top: 5vh;
    
}

.title {
    display: flex;
    justify-content: center;
    padding-bottom: 2vh;
}

.followUp {
    display: flex;
    justify-content: center;
}

* {
  font-family: Montserrat, sans-serif;
}

.cursor {
  display: inline-block;
  height: 40px;
  width: 2px;
  background: #aaa;
  vertical-align: middle;
  animation: 1s blink linear infinite;
}
@keyframes blink {
  0%,49% {
    opacity: 0;
  }
  50%,100% {
    opacity: 1;
  }
}

</style>
