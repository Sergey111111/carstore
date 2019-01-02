<template>
  <div class="row">
    <div class="col-xs-5 col-md-3 col-lg-4 vcenter">
      <p>Enter car name: </p>
      <input v-model="name" placeholder="name">
      <p>Enter car body type: </p>
      <input v-model="type" placeholder="type">
      <p>Enter car color: </p>
      <input v-model="color" placeholder="color">
      <p>Enter car price: </p>
      <input v-model="price" placeholder="price">
      <p>Write the description: </p>
      <textarea v-model="text" placeholder="description"></textarea>
    </div>
    <div class="col-xs-5 col-md-7 col-lg-8 vcenter">
      <h3>That's how the other users see your adv</h3>
      <p>Advertisement # created by {{user}}</p>
      <p>Car: {{ name }}</p>
      <p>Body type: {{ type }}</p>
      <p>Color: {{ color }}</p>
      <p>Price: {{ price }}</p>
      <p>Description: {{ text }}</p>
    </div>


  </div>
</template>

<script>
  export default {
    props: ['user'],
    data() {
      return {
        name: '',
        type: '',
        color: '',
        price: '',
        text: '',
      }
    }
  }
</script>

<style>

</style>
