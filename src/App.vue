<template>
  <div class="container">
    <h1 class="text-center">Paises Api</h1>
    <CardList />
  </div>
</template>

<script>
import CardList from './components/CardList.vue'
export default {
  name: 'App',
  components: {
    CardList
  }
}
</script>