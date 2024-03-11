<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <h1 class="heading">home</h1>
    <p class="text">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sapien ante, mattis eget aliquet auctor,
      molestie
      at massa. Interdum et malesuada fames ac ante ipsum primis in faucibus. Cras maximus eleifend tempor. Morbi varius
      mi vel nunc sollicitudin egestas. Integer a consequat nisl. Curabitur quis sagittis leo. Suspendisse in venenatis
      lectus, vitae facilisis mauris. Mauris dapibus urna id molestie porttitor. Proin et iaculis arcu. In et augue
      sapien. Donec sollicitudin felis quis ipsum mollis, id feugiat risus ultricies. Orci varius natoque penatibus et
      magnis dis parturient montes, nascetur ridiculus mus. Vestibulum nisi dolor, pretium et erat vel, congue suscipit
      dolor.
    </p>
  </div>
</template>

<style scoped>
.heading {
  color: brown;
}

.text {
  color: grey;
}
</style>