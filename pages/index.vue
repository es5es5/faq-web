<template>
  <div>
    FAQ
    <button type="button" @click="goCreate">faq</button>
  </div>
</template>

<script>
export default {
  name: 'Index',
  methods: {
    goCreate () {
      this.$router.push({
        name: 'faq'
      })
    }
  }
}
</script>
