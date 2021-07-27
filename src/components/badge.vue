<template lang="">
    <div class= "m-4">
        <span type="badge" v-bind:class="css">{{text}}</span>
    </div>
</template>
<script>
export default {
    name: 'Badge',
    props: ['text', 'type'],
    data() {
        return {
            css: 'badge bg-Dark'
            }   
   },
   methods: {
        init: function() {
            if (this.type != null) {
                this.css = 'btn btn-' + this.type;
            }
        }
    },
    mounted: function() {
        this.init()
    }

}
</script>
<style lang="">
    
</style>