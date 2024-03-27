<template>
  <button 
    class="ingrediente"
    @click="selecionado = !selecionado"
    >
      <Tag 
        :texto="ingrediente"
        :ativa="selecionado"
      />
  </button>
</template>

<script>
import Tag from './Tag.vue';
export default {
  components: {
    Tag
  },
  props: {
    ingrediente: {
      type: String,
      required: true
    }
  },
  data() {
    return {
      selecionado: false
    }
  },  
}
</script>

<style>
.ingrediente {
  cursor: pointer;
}
</style>