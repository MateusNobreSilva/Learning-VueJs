<template>
  <div>
    <PrimeiroComponente />
    <p>O dado de app é {{ testand }}</p>
    <LifeCicle />
    <Pessoa />
  </div>
</template>




<script>
import PrimeiroComponente from "./components/PrimeiroComponente.vue";
import LifeCicle from "./components/LifeCycle.vue";
import Pessoa from "./components/Pessoa.vue";

export default {
  name: "App",
  components: {
    PrimeiroComponente,
    LifeCicle,
    Pessoa,
  },
  data() {
    return {
      testand: "teste",
    };
  },
};
</script>
