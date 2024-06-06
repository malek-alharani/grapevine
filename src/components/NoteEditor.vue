<template>
  <div class="note-editor p-4 h-full bg-gray-800">
    <h2 class="text-lg font-bold mb-4 ">Enter your note</h2>
    <textarea v-model="noteContent" class="w-full h-64 p-2 border border-gray-300 rounded" placeholder="Type your note here..."></textarea>
    <button @click="saveNote" class="mt-4 px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-700">Save Note</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      noteContent: ''
    };
  },
  methods: {
    saveNote() {
      if (this.noteContent.trim()) {
        // Save the note (this can be expanded to save to a store or backend)
        console.log('Note saved:', this.noteContent);
        this.noteContent = ''; // Clear the text area
      } else {
        alert('Note content cannot be empty');
      }
    }
  }
};
</script>

<style scoped>
.note-editor {
  height: calc(100vh - 50px); /* Adjust height to account for toolbar */
}
</style>
