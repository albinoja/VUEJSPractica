<template>
  <div
    id="app"
    class="flex flex-col items-center justify-center min-h-screen p-6"
  >
    <h1 class="text-3xl font-bold text-center mb-4">¡Bienvenido!</h1>
    <BotonComponent texto="Haz clic aquí" />
  </div>
</template>

<script>
import BotonComponent from "./components/BotonComponent.vue";

export default {
  components: {
    BotonComponent,
  },
};
</script>

<style scoped>
/* Puedes agregar estilos adicionales aquí si es necesario */
</style>
