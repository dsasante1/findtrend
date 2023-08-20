
<script setup>
defineProps(['imageSrc', 'text', ])
</script>



<template>
        <span class="socialMedialCard">
             <img alt="text" class="socialMediaImage"  src={{imageSrc}}/>
             <span class="socialMediaText">{{ text }}</span>
             <img alt="closeIcon" class="closeIcon" src="@/assets/Group 1.svg"/>
        </span>

</template>


<style scoped>

.socialMedialCard{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;

    display: flex;
    gap: 20px;


}

.socialMediaImage{
    width: 25px;
}

.socialMediaText{
    color: white;
}


.closeIcon{
    width: 20px;
}

</style>
    