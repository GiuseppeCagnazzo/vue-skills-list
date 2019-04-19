<template>
    <div class="about">
        <h1>Hello {{ their_name }}, This is an about page</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto, esse mollitia! Labore autem ratione asperiores accusantium dolor consequuntur quos assumenda?</p>
    </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>

