<!-- Main page block -->
<template>
    <div >
  <b-jumbotron class= container>
    <template #header>A website... Work in progress!</template>

    <template #lead>
      Coming soon
    </template>

    <hr class="my-4">
  </b-jumbotron>
</div>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>
<style scoped>
.navbar{
    background: #f44336;
    padding: 1rem;
    font-size: 1.5rem;
    border-bottom: 1px solid white;


}
.container {
    height: 90vh;
    overflow: auto;
}
.navLink{
text-align: center;
}
a{
    text-decoration: none;
    padding: 1rem;
    color:#fff;
    text-align: center;
}
@media only screen and (max-width: 600px) {
    .navLink{
        display: flex;
        flex-direction: column;
    }
}
</style>
