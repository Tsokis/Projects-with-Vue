<template>
    <div class="about">
        <h1>Hello {{ their_name }}, This is the About page</h1>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim veniam consectetur, delectus optio modi praesentium architecto ipsum in repellat facere aliquid debitis harum accusamus, nulla ipsa? Explicabo, inventore? Eaque, inventore. </p>
    </div>
</template>

<script>
export default {
  name: "skills",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>

