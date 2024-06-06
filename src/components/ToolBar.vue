<template>
  <div class="toolbar p-4 bg-gray-400 text-white flex justify-between items-center">
    <h1 class="text-xl font-bold">Grapevine Notes</h1>
    <div>
      <!-- Add toolbar buttons or icons here -->
      <button class="ml-2 px-4 py-2 bg-blue-500 rounded hover:bg-blue-700">Add Note</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ToolBar',
};
</script>

<style scoped>
.toolbar {
  height: 50px;
}
</style>
