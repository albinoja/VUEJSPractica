<template>
  <div
    class="bg-bottom bg-gray-400 bg-no-repeat h-48 w-64"
    style="
      background-image: url('https://tailwind.build/placeholders/pictures/office.jpg');
      background-size: 12rem 8rem;
    "
  >
    <button
      class="duration-100 transform hover:scale-125 transition ease-linear bg-teal-400 px-6 py-2 m-4 inline"
    >
      {{ texto }}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    texto: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
/* Si necesitas agregar CSS personalizado, también puedes hacerlo aquí */
</style>
