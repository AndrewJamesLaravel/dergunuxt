<template>
  <div>
    <h4>Главная</h4>
    <button @click="showMessageFromBackend">Show message from backend</button>
  </div>
</template>
<script>
export default {
  methods: {
    async showMessageFromBackend() {
      try {
        const response = await this.$axios.get('/api/test')
        // eslint-disable-next-line no-console
        console.log(response.data)
      } catch (err) {
        // eslint-disable-next-line no-console
        console.log(err)
      }
    },
  },
  head() {
    return {
      title: 'Тестовый тайтл',
      meta: [
        { hid: 'description', name: 'description', content: 'Тестовый деск' },
      ],
    }
  },
  layout: 'main',
}
</script>

<style></style>
