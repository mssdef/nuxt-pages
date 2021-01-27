<template>
  <div className="block">
    <h2>Users page select</h2>
    <input type="text" v-model="userId" />
    <button @click="onLoadUser">Load User</button>

    <nuxt-child />
  </div>
</template>

<script>
  export default {
    data() {
      return {
        userId: ''
      }
    },
    methods: {
      onLoadUser() {
        this.$router.push('/users/' + this.userId);
      }
    },
    layout: 'users'
  }
</script>
