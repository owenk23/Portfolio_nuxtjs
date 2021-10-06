<!-- Main page block -->
<template>
    <div>
        <div class = container>
        
            <div class = profilePic>
              
               <img src="https://avatars.githubusercontent.com/u/45485947?v=4" alt="Owen's Proifile picture" class = ppicture> 

            </div>

            <div class = followUp>
                Hi, I'm Owen.
                I'm a 3rd year student and part time tinkerer. I am currently studying Computer science at the University of Portsmouth.
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
<style>
.container {
    /* This is the css for the big box */
    height: 60vh;
    margin-top: 30vh;
    background-color: rgba(0, 0, 0, 0.1);
    padding-top: 5vh;
    
}

.ppicture{
  border-radius: 50%;

}


.profilePic{
  display: flex;
  justify-content: center;
  margin: -20vh
}

.title {
    display: flex;
    justify-content: center;
    padding-bottom: 2vh;
}

.followUp {
    display: flex;
    justify-content: center;
    margin-top: 25vh;
    font-size: 40px;
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
