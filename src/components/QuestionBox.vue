<template>
   <div class="question-box-container">
    <b-jumbotron>
         <template v-slot:lead>
      Some question here
    </template>

    <hr class="my-4">

    <p>
      list of anwser
    </p>

    <b-button variant="primary" href="#">Submit</b-button>
    <b-button variant="success" href="#">next</b-button>
    </b-jumbotron>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>