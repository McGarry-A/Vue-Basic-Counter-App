<template>
  <button @click="increment">+</button>
  <h2>{{ count }}</h2>
  <button @click="decrement">-</button>
</template>

<script>
export default {
  name: "Counter",
  data: () => {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      return (this.count += 1);
    },
    decrement() {
      return (this.count -= 1);
    },
  },
};
</script>

<style></style>
