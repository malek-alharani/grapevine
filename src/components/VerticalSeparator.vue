<template>
  <div class="vertical-separator "></div>
</template>

<script>
export default {
  name: 'VerticalSeparator',
};
</script>

<style scoped>
.vertical-separator {
  width: 25px;
  background-color: red;
  height: calc(100vh - 50px); /* Adjust height to account for toolbar */
}
</style>
