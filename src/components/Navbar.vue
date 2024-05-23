<template>
  <nav>
    <h1>Navbar</h1>
    <Button :title="title" :color="color" />
  </nav>
</template>

<script>
  import Button from "./Button.vue";

  export default {
    name: "Navbar",
    props: {
      title: String,
      color: String,
    },
    components: {
      Button,
    },
  };
</script>
