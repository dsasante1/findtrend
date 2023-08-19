
<script setup>
defineProps(["buttonText"])

</script>

<template>

<div class="positionButton">

<span class="buttonStyle">{{buttonText}}
</span>

</div>


</template>


<style scoped>

.buttonStyle{
    border-radius: 20px;
    padding: 10px;
    padding-right: 20px;
    padding-left: 20px;
    color: black;
    background-color: yellowgreen;
}


</style>
    