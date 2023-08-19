
<script setup>
import {ref} from 'vue'

import TheCardComponent from './TheCardComponent.vue'
import TheGreenButton from './TheGreenButton.vue'
import TheBlackButton from './TheBlackButton.vue'


const cardOne = ref({
    "title": "Personal",
    "subtitle": "Special first packet for all",
    "cost":"8",
    "userOptions": [
        "Up to 5 page each group",
        "Up to 10 group page" ,
        "5 Days group page saved",
    ]
})


const cardTwo = ref({
    "title": "Regular",
    "subtitle": "Recommended for personal pro",
    "cost":"20",
    "userOptions": [
        "Up to 15 page each group",
        "Download page up to 20 page" ,
        "Up to 10 group page",
        "15 Days group page saved"
    ]
})



const cardThree = ref({
    "title": "Premium",
    "subtitle": "Packet for Startup & Company",
    "cost": "48",
    "userOptions": [
        "Unlimited group pages",
        "Unlimited download page",
        "Unlimited page each group",
        "Custormized sorting group pages",
        "Custormized group page name",
        "30 Days group page saved",
    ]
})


</script>


<template>

    <div id="mobileView">
        <div class="cards">
        <p id="dealText">Get your best deal</p>

        <div class="dealOptions">
            <span id="option">Monthly</span>
            <label class="switch">
            <input type="checkbox">
            <span class="slider round"></span>
          </label>
            <span id="option">Yearly</span>

        </div>
        <img alt="arrow" id="arrow" src="@/assets/Arrow 5.svg"/>
        <img alt="discount" id="discount" src="@/assets/discount.png"/>

        <div id="optionCard">
            <span id="cardOne">
                <h1>Personal</h1>
                <h3>Special first packet for all</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$8</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 5 page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 10 group page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>5 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionOne">
                    <span id="freeTrial">Start Free Trial</span>
                </div>

            </span>

            <span id="cardTwo">
                <h1>Regular</h1>
                <h3>Recommended for personal pro</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$20</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 15 page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Download page up to 20 page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 10 group page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>15 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionTwo">
                    <span id="freeTrialTwo">Start Free Trial</span>
                </div>
            </span>

            <span id="cardThree">
                <h1>Premium</h1>
                <h3>Packet for Startup & Company</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$48</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited group pages</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited download page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Custormized sorting group pages</span>
                    </div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Custormized group page name</span>
                    </div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>30 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionThree">
                    <span id="freeTrial">Start Free Trial</span>
                </div>
            </span>
        </div>
    </div>
    </div>



<div id="desktopView">
    <div class="cards">
        <p id="dealText">Get your best deal</p>

        <div class="dealOptions">
            <span id="option">Monthly</span>
            <label class="switch">
            <input type="checkbox">
            <span class="slider round"></span>
          </label>
            <span id="option">Yearly</span>

            <img alt="arrow" id="arrow" src="@/assets/Arrow 5.svg"/>
            <img alt="discount" id="discount" src="@/assets/discount.png"/>

        </div>

        <div id="optionCard">
            
            <TheCardComponent id="cardOne" :title=cardOne.title :subtitle=cardOne.subtitle :cost=cardOne.cost :userOptions=cardOne.userOptions />
           
          

            <TheCardComponent id="cardTwo" :title=cardTwo.title :subtitle=cardTwo.subtitle :cost=cardTwo.cost :userOptions=cardTwo.userOptions />
            

            <TheCardComponent id="cardThree" :title=cardThree.title :subtitle=cardThree.subtitle :cost=cardThree.cost :userOptions=cardThree.userOptions />
            

        


            <!-- <span id="cardOne">
                <h1>Personal</h1>
                <h3>Special first packet for all</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$8</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 5 page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 10 group page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>5 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionOne">
                    <span id="freeTrial">Start Free Trial</span>
                </div>

            </span>

            <span id="cardTwo">
                <h1>Regular</h1>
                <h3>Recommended for personal pro</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$20</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 15 page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Download page up to 20 page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Up to 10 group page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>15 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionTwo">
                    <span id="freeTrialTwo">Start Free Trial</span>
                </div>
            </span>

            <span id="cardThree">
                <h1>Premium</h1>
                <h3>Packet for Startup & Company</h3>
                <br>
                <hr>
                <br>
                <span id="cost">$48</span><span>/Month</span>
                <div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited group pages</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited download page</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Unlimited page each group</span>
                    </div>

                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Custormized sorting group pages</span>
                    </div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>Custormized group page name</span>
                    </div>
                    <div>
                        <img alt="checkMark" id="checkMark" src="@/assets/Frame 29.svg"/>
                        <span>30 Days group page saved</span>
                    </div>

                </div>

                <div id="freeTrialPositionThree">
                    <span id="freeTrial">Start Free Trial</span>
                </div>
            </span> -->
        </div>
        <TheGreenButton class="buttonPositionOne" buttonText='start free trial' />
        <TheBlackButton class="buttonPositionTwo" buttonText='start free trial' />
        <TheGreenButton class="buttonPositionThree" buttonText='start free trial' />
    </div>

</div>


</template>



<style scoped>


@media only screen and (max-width: 900px){

    #desktopView{
        display: none;
    }

    .cards{
    background-color: black;
}



#dealText{
    color: white;
    padding-top: 100px;
    padding-bottom: 50px;
    padding-left: 10px;
    padding-right: 10px;
    text-align: center;
    font-size: 39px;
    font-weight:1000;

}




#option{
    color:white;
}

.dealOptions{
    display: flex;
    flex-direction: row;
    gap: 10px;
    align-items: center;
    justify-content: center;
    padding-bottom: 30px;

}


.switch {
    position: relative;
    display: inline-block;
    width: 50px;
    height: 23px;

  }

  .switch input {
    opacity: 0;
    width: 0;
    height: 0;
  }

  .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: yellowgreen;
    -webkit-transition: .4s;
    transition: .4s;
  }

  .slider:before {
    position: absolute;
    content: "";
    height: 20px;
    width: 20px;
    left: 4px;
    bottom: 2px;
    background-color: white;
    -webkit-transition: .4s;
    transition: .4s;
  }

  input:checked + .slider {
    background-color: yellowgreen;
  }

  input:focus + .slider {
    box-shadow: 0 0 1px yellowgreen;
  }

  input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(26px);
  }

  /* Rounded sliders */
  .slider.round {
    border-radius: 34px;
  }

  .slider.round:before {
    border-radius: 50%;
  }


  #arrow{
    position: relative;
    bottom: 40px;
    left: 240px;
  }


#discount{
    position: relative;
    left: 190px;
    width: 90px;
    top: 10px;
}

  #optionCard{
    display: flex;
    flex-direction: column;
    gap: 30px;
    align-items: center;
    justify-content: center;
    padding: 50px;
  }



#cardOne{
    width: 320px;
    height: 650px;
    background-color: white ;
    border-radius: 5px;
    padding: 20px;

}

#cardTwo{
    width: 320px;
    height: 650px;
    background-color: yellowgreen;
    border-radius: 5px;
    padding: 20px;
}

#cardThree{
    width: 320px;
    height: 650px;
    background-color: white ;
    border-radius: 5px;
    padding: 20px;
}


#freeTrialPositionOne{
    padding-top: 230px;
    padding-right: 20px;
    padding-left: 20px;
}


#freeTrialPositionTwo{
    padding-top: 170px;
    padding-right: 20px;
    padding-left: 20px;
}



#freeTrialPositionThree{
    padding-top: 100px;
    padding-right: 20px;
    padding-left: 20px;
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

#freeTrialTwo{
    background-color: black;
    color: white;
    border-radius: 50px;
    padding: 10px;
    padding-left : 40px;
    padding-right: 40px;
    font-size: large;

}

#cost{
    font-size: 70px;
    font-weight: bolder;
}



}




@media only screen and (min-width: 900px){

#mobileView{
    display: None;
}


.cards{
    background-color: black;
}



#dealText{
    color: white;
    padding-top: 70px;
    padding-bottom: 50px;
    padding-left: 200px;
    padding-right: 200px;
    text-align: center;
    font-size: 30px;
    font-weight: bolder;

}


#option{
    color:white;
}

.dealOptions{
    display: flex;
    flex-direction: row;
    gap: 10px;
    align-items: center;
    justify-content: center;
    padding-bottom: 30px;

}


.switch {
    position: relative;
    display: inline-block;
    width: 50px;
    height: 23px;

  }

  .switch input {
    opacity: 0;
    width: 0;
    height: 0;
  }

  .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: white;
    -webkit-transition: .4s;
    transition: .4s;
  }

  .slider:before {
    position: absolute;
    content: "";
    height: 20px;
    width: 20px;
    left: 4px;
    bottom: 2px;
    background-color: yellowgreen;
    -webkit-transition: .4s;
    transition: .4s;
  }

  input:checked + .slider {
    background-color: white;
  }

  input:focus + .slider {
    box-shadow: 0 0 1px yellowgreen;
  }

  input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(26px);
  }


  .slider.round {
    border-radius: 34px;
  }

  .slider.round:before {
    border-radius: 50%;
  }

  #optionCard{
    display: flex;
    flex-direction: row;
    gap: 30px;
    align-items: center;
    justify-content: center;
    padding: 50px;
  }



  #arrow{
    position: relative;
    top: 40px;
    right: 60px;
  }


#discount{
    position: relative;
    top: 90px;
    right: 110px;
    width: 90px;
    padding-bottom: 20px;

}






#cardOne{
    width: 320px;
    height: 650px;
    background-color: white ;


}

#cardTwo{
    width: 320px;
    height: 650px;
    background-color: yellowgreen;

}

#cardThree{
    width: 320px;
    height: 650px;
    background-color: white ;

}


.buttonPositionOne{
    z-index: 1;
    position: relative;
    bottom:130px;
    left: 200px;
}


.buttonPositionTwo{
    z-index: 1;
    position: relative;
    bottom:150px;
    left: 550px;
}



.buttonPositionThree{
    z-index: 1;
    position: relative;
    bottom:170px;
    left: 900px;
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

#freeTrialTwo{
    background-color: black;
    color: white;
    border-radius: 50px;
    padding: 10px;
    padding-left : 40px;
    padding-right: 40px;
    font-size: large;

}

#cost{
    font-size: 70px;
    font-weight: bolder;
}


}



</style>
