<template>
  <div id="app" class="flex flex-col h-screen">
    <ToolBar />
    <div class="flex flex-grow">
      <div class="w-1/3">
        <NoteTree />
      </div>
      <VerticalSeparator />
      <div class="w-2/3">
        <TipTap />
      </div>
    </div>
  </div>
</template>

<script>
import ToolBar from './components/ToolBar.vue';
import NoteTree from './components/NoteTree.vue';
//import NoteEditor from './components/NoteEditor.vue';
import VerticalSeparator from './components/VerticalSeparator.vue';
import TipTap from './components/TipTap.vue'

export default {
  name: 'App',
  components: {
    ToolBar,
    NoteTree,
//    NoteEditor,
    VerticalSeparator,
    TipTap
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
