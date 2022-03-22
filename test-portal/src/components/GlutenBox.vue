<template>
  <div>
      <input type="checkbox" id="checkbox-gluten" disabled="disabled" />
      <label for="checkbox-gluten">¿Tiene gluten?</label>
  </div>
</template>

<script>
export default {
    props : {
        marked : { type : Boolean, required : true , default : true}
    }
}
</script>

<style>

</style>