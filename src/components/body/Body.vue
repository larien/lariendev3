<template>
  <section id="body">
    <h1>
      <p>Hello!</p>
      <p>My name is <span title="aka larienmf">Lauren</span> and I'm</p>
    </h1>
    <typewriter/>
    <h1>
      <p>based in <span title="the magic island!">Florianópolis</span>, <span title="#ELENÃO">Brazil</span>.</p>
    </h1>
  </section>
</template>

<script>
import Typewriter from "./Typewriter.vue";

export default {
  components: 
  { Typewriter }
}
</script>

<style>
#body {
  font-size: 2rem;
  flex-wrap: wrap;
  display: flex;
  justify-content: space-around;
  align-content: center;
  cursor: default;
  line-height: 80px;
}

h1 {
  color: white;
}

span {
  color: #1da1eb;
  font-weight: bold;
}

</style>