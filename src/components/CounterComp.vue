<template>
  <h1>{{ testNumber }}</h1>
  <button @click="testNumber++">increment</button>
  <button @click="testNumber--">decrement</button>
</template>

<script>
export default {
  name: "CounterComp",
  data: () => {
    return {
      testNumber: 0,
    };
  },
};
</script>
