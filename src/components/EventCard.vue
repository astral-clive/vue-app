<template>
  <div>
    <h2>{{ msg }}</h2>
    <p>{{ quote }}</p>
  </div>
</template>

<script>
export default {
  props: ['msg'],
  data() {
    return {
      quote: 'Museum in Rotenburg.'
    }
  }
}
</script>

<style></style>
