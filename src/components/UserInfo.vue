<template>

  <div align="left">
    <div class="d-flex justify-content-center">
      <div class="image_outer_container">
        <div class="image_inner_container">
          <div><img
            src="https://lh5.googleusercontent.com/-bcLREXN4a-4/AAAAAAAAAAI/AAAAAAAAEMA/NCd2eyGJ8z0/photo.jpg"/>
          </div>
        </div>
      </div>
    </div>
    <div class="menu">
      <ul class="nav sidebar-nav">
        <li class="sidebar-brand">
          <a href="#">
            Profile
          </a>
        </li>
        <li>
          <a href="#"
             @click="$emit('add')"
          >Add new</a>
        </li>
        <li>
          <a href="#">Messages</a>
        </li>
        <li>
          <a href="#"
             @click="$emit('showAll')"
          >Top advs</a>
        </li>
        <li>
          <a href="#"
             @click="$emit('logOut')"
          >Log out</a>
        </li>
      </ul>
    </div>
  </div>

</template>

<script>

</script>

<style scoped>
  html, body {
    height: 100%;
  }

  .container {
    height: 100%;
    align-content: center;
  }

  .image_outer_container {
    margin-top: auto;
    margin-bottom: auto;
    border-radius: 50%;
    position: relative;
  }

  .image_inner_container img {
    height: 150px;
    width: 150px;
    border: 5px solid white;
  }

  img {
    width: inherit;
    height: inherit;
  }

  .menu {
    align-content: center;
  }
</style>
