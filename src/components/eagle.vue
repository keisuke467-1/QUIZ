<template>
  <div class="alert alert-info">
    <h2 style="color:red">{{ title }}</h2>
    <p>{{ message }}</p>
    <div class="p-3 mb-2 bg-warning text-dark">{{ comment }}</div>
  </div>
</template>

<script>
export default {
  name: 'eagle',
  props: {
    title: String,
    message: String,
    comment: String,
  }
}
</script>