<template>
    <div>
        <li class="item">{{item}}</li>
    </div>
</template>

<script>
    export default {
        props:["item"],
    }
</script>

<style>
    .item{
        color:red
    }
</style>