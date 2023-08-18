
<script setup></script>
<template>
    <div class="footerContents">
        <p id="joinUs">Join us on email for</p>
        <p id="trendingTopics">more trending topics</p>
        <div  id="joinNow"><span>Join Now</span></div>
    </div>
    <div class="footerUrls">
            <span>
                <img alt="blackLogo" id="blackLogo" src="@/assets/Vector.svg"/>             
                <span>Findtrend</span>
            </span>
            <span id="footerNavUrls">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms and Conditions</a>
                <a href="#">Contact Us</a>
                <a href="#">Careers</a>

            </span>
    
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
    padding: 20px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}


#footerNavUrls{
    display: flex;
    flex-direction: row;
    gap: 20px;
 


}

#footerNavUrls a{
    text-decoration : none;
    color: black;
}

</style>
    