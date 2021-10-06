
<template>

  <div>
    <div class = title>
      <vue-typed-js :loop="true" :cursorChar="'_'" :startDelay="1000" :strings="['A website', 'An opportunity', 'An inspiration']">
        <h1>
          <span class="typing"></span>... by me
        </h1>
      </vue-typed-js>
    </div>
    

  </div>
</template>
<script>

</script>
<style scoped>
.title {
    display: flex;
    justify-content: center;
    padding-top: 40vh;

}

</style>