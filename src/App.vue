<style>
  form{
    display: block;
    height: 400px;
    width: 400px;
    background: #ccc;
    margin: auto;
    margin-top: 40px;
    text-align: center;
    line-height: 400px;
      border-radius: 4px;
  }
</style>

<template>
  <div id="file-drag-drop">
    <form ref="fileform">
        <span class="drop-files">Drop the files here!</span>
    </form>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        dragAndDropCapable: false,
        files: []
      }
    }
  }
</script>
