<template>
  <h1>{{ titleMessage }}</h1>
</template>

<script>
export default {
  name: 'TestComp',
  props: {
    titleMessage: String
  }
}
</script>