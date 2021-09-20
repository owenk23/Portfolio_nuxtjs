<template>
  <div :style="myStyle" id="wrapper">
    <Header/>
    <MainContent/>
    <PrintCarousel/>
    <Footer/>
  </div>
</template>

<script>
export default {
  data(){
    return{
      myStyle:{
        backgroundColor: "rgb(86, 136, 165)"
      }
    }      
                
  }
}
</script>



