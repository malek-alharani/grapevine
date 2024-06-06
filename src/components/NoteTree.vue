<template>
  <div class="note-tree p-4 bg-gray-100 h-full">
    <h2 class="text-lg font-bold mb-4">Notes Tree</h2>
    <!-- Note tree structure goes here -->
    <ul>
      <li>Note 1</li>
      <li>Note 2</li>
      <li>Note 3</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NoteTree',
};
</script>

<style scoped>
.note-tree {
  height: calc(100vh - 50px); /* Adjust height to account for toolbar */
}
</style>
