<template>
  <div class="container">
    <p v-if="$auth.loggedIn">Name：{{ $auth.user.name }}</p>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
