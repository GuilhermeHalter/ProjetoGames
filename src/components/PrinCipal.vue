<script>
import NovoBloco from "@/components/NovoBloco.vue";
export default {
  components: { NovoBloco },
};
</script>
<template>
  <main id="content">
    <NovoBloco titulo="Bloco 1" :nomes="['guilherme', 'samuel']"/>
    <NovoBloco />
    <NovoBloco titulo="Urgente" :nomes="['guilherme', 'samuel']"/>
    <NovoBloco />
    <NovoBloco />
    <NovoBloco class="blokead"/>
  </main>
</template>
<style></style>