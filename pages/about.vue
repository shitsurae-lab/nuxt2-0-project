<template>
  <div>
    <h1>{{ `${title}` }}</h1>
    <img :src="require(`~/assets/images/${fileName}.jpg`)" />
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: 'This is About page',
      fileName: 'paris-480square',
    }
  },
}
</script>
