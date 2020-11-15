<template>
  <div>
    <header1 />
    test
    <Nuxt />
  </div>
</template>

<script>
import Header1 from '@/components/header-1'
export default {
  components: { Header1 },
  head() {
    return {
      link: [
        { rel: 'canonical', href: `http://localhost:3000${this.$route.path}` },
      ],
    }
  },
}
</script>

<style></style>
