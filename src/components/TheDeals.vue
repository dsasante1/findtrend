
<script setup></script>
<template>
    <div class="deals">
        <p id="dealText">Get your best deal</p>
    
        <div class="dealOptions">
            <span id="option">Monthly</span>
            <label class="switch">
            <input type="checkbox">
            <span class="slider round"></span>
          </label>
            <span id="option">Yearly</span>
            <img alt="arrow" id="arrow" src="@/assets/Arrow 03.svg"/>
    
        </div>

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
</template>



<style scoped>

.deals{
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

  #optionCard{
    display: flex;
    flex-direction: row;
    gap: 30px;
    align-items: center;
    justify-content: center;
    padding: 20px;
  }



#cardOne{
    width: 300px;
    height: 650px;
    background-color: white ;
    border-radius: 5px;
    padding: 20px;

}

#cardTwo{
    width: 300px;
    height: 650px;
    background-color: yellowgreen;
    border-radius: 5px;
    padding: 20px;
}

#cardThree{
    width: 300px;
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

</style>
    