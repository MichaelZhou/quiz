<template>
    <div>
  <b-nav tabs> <!-- Adds a line underneath the title and counter -->
    <b-nav-item disabled><b>Michael's Quiz App</b></b-nav-item>
    <b-nav-item disabled>Counter: {{ numCorrect }} / {{ numTotal}} </b-nav-item>
  </b-nav>
    </div>
</template>


<script>
export default {
    props: [
        'numCorrect', // receiving the number of correct and total answers from the parent
        'numTotal'
    ]
}
</script>