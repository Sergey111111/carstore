<template>
  <div class="container-fluid">
    <p>Google authorization required </p>
    <ul class="nav sidebar-nav">
      <li class="sidebar-brand alert-warning">
        <a href="#"
           @click="$emit('authorize')">
          Log-in
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: "Unlogged"
  }
</script>

<style scoped>

</style>
