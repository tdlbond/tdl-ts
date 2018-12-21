<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h2 v-text="message"></h2>
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: 'hello world!!!  ---testdev'
    }
  }
}
</script>

