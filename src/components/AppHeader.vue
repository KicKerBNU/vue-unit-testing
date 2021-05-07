<template lang="pug">
  div
    button(v-show="loggedIn") Logout
</template>

<script>
export default {
  data() {
    return {
      loggedIn: false
    }
  }
}
</script>