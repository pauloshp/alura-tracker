<template>
  <div class="box has-text-weight-bold">
    <div class="columns">
      <div class="column is-7">Descricão da tarefa</div>
      <div>
        <Cronometro tempoEmSegundos="15"/>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Cronometro from './Cronometro.vue'

export default defineComponent({
  name: 'Tarefa',
  components: {
    Cronometro
  }
})
</script>

<style scoped>
.box {
  background: #FAF0CA;
}
</style>
