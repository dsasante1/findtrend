
<script setup></script>
<template>

    <div class="mobileView">
        <div id="navSection">
            <div id="mobileNav">
            
            <img alt="mobileGreenLogo" id="mobileGreenLogo" src="@/assets/green_logo.svg"/>
            <img alt="menu" id="menu" src="@/assets/twostrips.svg"/>  

            </div>
            <p id="navTitle">Minimize your tabs.</p>
            <p id="navTitle">Find the trends!</p>
            <p id="navSubTitle">
                Don’t let your computer 
                memories consumes
                 all of those browser tabs. 
                Findtrend  let you gathers all of 
                your favorite website into one place.
            </p>
            <span id="getStarted">
                <img alt="get-started" id="getStartedImage" src="@/assets/Get Started 🔥.svg"/>
            </span>
            <div id="socialMedia">
        <span id="cardTwitter">
             <img alt="cardTwitter"  src="@/assets/image 96.png"/>
             <span id="socialMediaText">Cryptopunk - Search</span>
             <img id="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>

        <span id="cardPininterest">
             <img alt="cardPininterest"  src="@/assets/image 96(1).png"/>
             <span id="socialMediaText">Popular Design - Search</span>
             <img id="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>


        <span id="cardFb">
             <img alt="cardFb"  src="@/assets/image 95.png"/>
             <span id="socialMediaText">Product Design - Search</span>
             <img id="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>
        




        <span id="cardDribble">
             <img alt="cardDribble" id="cardDribbleImage"  src="@/assets/Rectangle 6.svg"/>
             <span id="socialMediaText">Elon Musk - Search</span>
             <img id="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>


    </div>
        </div>
    </div>



    <div class="desktopView">
    <div class="nav">
    <div class="navItems">
    <span>
        <img alt="findtrend logo" class="greenLogo" src="@/assets/green_logo.svg"/>
        <span class="logoText">Findtrend</span>
    </span>
    <span class="navLinks">
        <a href="#">About</a>
        <a href="#">How it works</a>
        <a href="#">Pricing</a>
        <a href="#">Solution</a>
        <a href="#">Features</a>
    </span>
    <span>
        <span id="login">Login</span>
        <span id="register">Register</span>
    </span>
</div>
<p id="minimizeText">
    Minimize your tabs.
    Find the trends!
</p>
<p id="subtitle">
    Don’t let your computer memories consumes all of those browser tabs. 
Findtrend  let you gathers all of your favorite website into one place.

</p>
    
        <img alt="flames" id="getStarted" src="@/assets/Get Started 🔥.svg"/> 
         <img alt="arrow" id="arrow" src="@/assets/Arrow 03.svg"/>
    
        <span id="researchHere">
            <img alt="research start here" src="@/assets/All research start from here.svg"/>
        </span>
    <div id="socialMedia">
        <span id="cardTwitter">
             <img alt="cardTwitter"  src="@/assets/image 96.png"/>
             <span id="socialMediaText">Cryptopunk - Search</span>
             <img alt="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>
        <span id="cardFb">
             <img alt="cardFb"  src="@/assets/image 95.png"/>
             <span id="socialMediaText">Product Design - Search</span>
             <img alt="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>
        

        <span id="cardPininterest">
             <img alt="cardPininterest"  src="@/assets/image 96(1).png"/>
             <span id="socialMediaText">Popular Design - Search</span>
             <img alt="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>


        <span id="cardDribble">
             <img alt="cardDribble"  src="@/assets/Rectangle 6.svg"/>
             <span id="socialMediaText">Elon Musk - Search</span>
             <img alt="closeIcon"  src="@/assets/Group 1.svg"/>
        </span>


    </div>
</div>

</div>



   
</template>



<style scoped>



@media only screen and (max-width: 900px){
.desktopView{
    display: None;
}

#navSection{
    padding: 20px;
    background-color: black;
    background-image: url('@/assets/Ornament.svg');
    /* background-repeat: no-repeat; */


}

#mobileNav{

    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-bottom: 70px;

}

#menu{
    width: 40px;
}

#navTitle{
    font-weight: bolder;
    font-size: 20px;
    color: white;
    text-align: center;
}

#navSubTitle{
    color: white;
    padding: 40px;
    opacity: 0.6;

}

#getStarted{
    background-color: greenyellow;
    padding: 10px;
    border-radius: 50px;
    position: relative;
    left: 100px;
}



#socialMedia{
    padding: 50px;
    display: flex;
    flex-direction: column;
    gap: 40px;
    
}




#socialMediaText{
    color: white;
    font-size: 15px;
}


#closeIcon{
    width: 20px;
}

#cardTwitter{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: -5deg;
    /* padding: 20px; */
}


#cardFb{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: -5deg;
    /* padding: 20px; */
}


#cardPininterest{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 302px;
    display: flex;
    gap: 20px;
    rotate: 15deg;
    /* padding: 20px; */
}


#cardDribbleImage{
    width: 30px;
    
}

#cardDribble{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: 15deg;
    /* padding: 20px; */
}







}



@media only screen and (min-width: 900px){


.mobileView{
    display: none;
}

.nav{
    background-color: black;
    padding: 30px;
    background-image: url('@/assets/Ornament.svg');
    /* background-repeat: no-repeat; */

}

.navItems{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}


.logoText{
    font-weight: bold;
    font-size: xx-large;
    color: white;
    padding-left: 20px;
   
    
   
}

.navLinks{
   
    display: flex;
    justify-content: space-evenly;
    gap: 40px;
    


}


.navLinks a{
    color: white;
    text-decoration : none;

}



#login{
    color: white;
    padding-right: 40px;
}
#register{
    background-color: white;
    color: black;
    border-radius: 50px;
    padding: 10px;
    padding-left : 40px;
    padding-right: 40px;
    font-size: larger;
}

#minimizeText{
    color: white;
    padding-top: 100px;
    padding-left: 300px;
    padding-right: 300px;
    font-weight: bolder;
    font-size: 50px;
    text-align: center;
}

#subtitle{
    color: lightgray;
    padding-top: 20px;
    padding-left: 330px;
    padding-right: 330px;
    font-weight: 400; 


}


#getStarted{
    position: relative;
    top: 40px;
    left: 480px;
}

#arrow{
    position: relative;
    top: 20px;
    left: 500px;
}

#researchHere{
    position: relative;
    bottom: 2px;
    left: 470px;

}



#getStarted{
    background-color: greenyellow;
    padding: 20px;
    border-radius: 50px;
 

}



#socialMedia{
    padding: 50px;
    display: flex;
    flex-direction: row;
    
}




#socialMediaText{
    color: white;
}


#cardTwitter{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: -5deg;
    /* padding: 20px; */
}


#cardFb{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: 15deg;
    /* padding: 20px; */
}


#cardPininterest{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 302px;
    display: flex;
    gap: 20px;
    rotate: -5deg;
    /* padding: 20px; */
}


#cardDribble{
    background-color: #181818;
    padding-left: 20px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 300px;
    display: flex;
    gap: 20px;
    rotate: 15deg;
    /* padding: 20px; */
}
}


</style>
    