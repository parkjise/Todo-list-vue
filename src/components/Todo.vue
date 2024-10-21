<script>
  export default {
    props:{
      todo:{
        type:Object,
        required:true
      }
    }
  }
</script>
<template>
  <div class="form-check">
    <input class="form-check-input" type="checkbox" value="" id="input{{todo.id}}">
    <label class="form-check-label" for="input{{todo.id}}">
      {{todo.text}}
    </label>
  </div>
</template>