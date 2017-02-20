<template>
    <div>
        <div>{{ msg }}</div>
        <div><input v-model="msg"></div>
    </div>
</template>
<style lang="sass">
    body {
        background-color: #efefef;
    }
</style>
<script>
    export default{
        data(){
            return{
                msg: 'hello vue'
            }
        }
    }
</script>
