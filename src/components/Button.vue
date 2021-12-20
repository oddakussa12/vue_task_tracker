<template>
    <button @click="addTask()" :style="{background:color}" >{{text}}</button>
</template>

<script>
    export default{
        name:"Button",
        props:{
            text:String,
            color:String
        },
        methods:{
            addTask(){
                console.log("clicked");
            }
        }
    }
</script>