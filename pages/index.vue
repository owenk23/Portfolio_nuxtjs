<template>
  <div :style="myStyle" id="wrapper">
    <Header/>
    <Heading/>
    <MainContent/>
    <PrintCarousel/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Contact from '../components/Contact.vue'
export default {
  components: { Contact },
  data(){
    return{
      myStyle:{
        backgroundColor: "rgb(86, 136, 165)"
      }
    }      
                
  }
}
</script>



