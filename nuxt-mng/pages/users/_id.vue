<template>
  <h2>Users ID {{ $route.params.id }}</h2>
</template>

<script>
  export default {
    validate(data) {
      return parseInt(data.params.id) == data.params.id;
    },
  }
</script>
