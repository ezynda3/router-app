<template>
  <div class="users">
    <h1>My name is {{ users[$route.params.id ] }}</h1>
  </div>
</template>

<script>
export default {
  name: 'users',
  data() {
    return {
      users: ['Tom', 'Mary', 'Bill']
    }
  }
}
</script>
