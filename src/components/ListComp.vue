<template>
  <ul>
    <li v-for="item in testItems" v-bind:key="item.id">{{ item.value }}</li>
  </ul>
</template>

<script>
export default {
  name: "ListComp",
  data: () => {
    return {
      testItems: [
        { id: 1, value: "MyTesT" },
        { id: 2, value: "MyTes2" },
        { id: 3, value: "MyTes3" },
      ],
    };
  },
};
</script>
