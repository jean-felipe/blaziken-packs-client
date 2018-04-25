<template>
  <div class="thumb-item">
    <div class="thum-image">{{ image }}</div>
    <div class="thumb-content">
      <div class="thumb-title">{{ name }}</div>
      <button class="thub-add">Adicionar</button>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ThumbItem',
  props: {
    name: String,
    description: String,
    price: String,
    image: String,
    quantity: String
  }
}
</script>
<style>

</style>
