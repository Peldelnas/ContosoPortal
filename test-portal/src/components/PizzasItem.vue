<template>
    <div>        
        <label for="pizza-name">{{label}}</label>
        <gluten-box :marked="isGlutenFree" />
    </div>
    
</template>

<script>
import GlutenBox from './GlutenBox.vue';

    export default {
  components: { GlutenBox },
        props: {
            id: { required: true, type: Int8Array},
            label : { default: "margarita", type: String},
            isGlutenFree : {default: false, type: Boolean}
        }
     };
</script>

