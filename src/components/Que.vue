<template>
  <div class="alert alert-info">
    <h2 style="color:red">{{ que }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'Que',
  props: {
    que: String,
    message: String,
  },
}
</script>