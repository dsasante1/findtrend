
<script setup></script>
<template>
    <div class="footerContents">
        <p id="joinUs">Join us on email for</p>
        <p id="trendingTopics">more trending topics</p>
        <div  id="joinNow"><span>Join Now</span></div>
        <div class="footerUrls">
            
        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>             
        <span>Findtrend</span>

        </div>

    </div>
</template>




<style scoped>

.footerContents{
    background-color: yellowgreen;
    padding: 50px;


}


#joinUs{
    font-size: 40px;
    font-weight: bolder;
    text-align: center;
    padding-top: 30px;
}

#trendingTopics{
    font-size: 40px;
    font-weight: bolder;
    text-align: center;
    padding-bottom: 30px;
    opacity: 0.2;
}

#freeTrial{
    background-color: yellowgreen;
    color: black;
    border-radius: 50px;
    padding: 10px;
    padding-left : 40px;
    padding-right: 40px;
    font-size: large;

}


#joinNow{
    display: flex;
    align-items: center;
    justify-content: center;
}


#joinNow span{
    font-size: small;
    background-color: black;
    color: white;
    border-radius: 50px;
    padding: 10px;
    padding-left : 40px;
    padding-right: 40px;
    
}

.footerUrls{

}

</style>
    