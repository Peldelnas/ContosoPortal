<template>
  <div>
      <input type="checkbox" id="checkbox-gluten" />
      <label for="checkbox-gluten">¿Tiene gluten?</label>
  </div>
</template>

<script>
export default {
    props : {
        marked : { type : Boolean, required : true }
    }
}
</script>

<style>

</style>