
<script setup>



defineProps(["title", "subTitle", "cost","userOptions"])




</script>


<template>

<span class="cardComponent">
    <h1>{{ title }}</h1>
    <h3>{{ subTitle }}</h3>
    <br>
    <hr>
    <br>
    <span class="cost">{{ cost }}</span><span>/Month</span>
    <div class="cardTexts">
        <div class="cardOptions" v-for="(index, value) of userOptions" :key="value">
            <img alt="checkMark" class="checkMark" src="@/assets/Frame 29.svg"/>
            <span>{{index}}</span>

        </div>


    </div>



</span>

</template>


<style scoped>

.cardComponent{
    border-radius: 5px;
    padding: 40px;

}


.cost{
    font-size: 70px;
    font-weight: bolder;
}

.cardTexts{
    padding-top: 40px;
}

.cardOptions{
    padding: 2px;
    display: flex;
    flex-direction: row;
    gap: 10px;
    align-items: center;
}

</style>
