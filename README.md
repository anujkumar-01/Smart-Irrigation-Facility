# Smart-Irrigation-Facility

This is a project that is made for a hackathon to highlight an idea which most people neglect, that is smart irrigation.

It project include two main components:
1. Data set. 
2. Prediction model that will predict the next season for automatic irrigation on the basis of user input .


## Inspiration 

In this busy world people always neglect their smartness. This model will help to make their day to day life a little easier . 


## What it does 
 
It takes input as weather predictions. And according to the conditions of weather it automatically start irrigation.
### Additional stuff 

We would like to add more precise way of providing weather conditions.

### Working

Step1: Connect the water pump to 13 and sensor to pin 8. Step2: Call for function setup();
Step3: Call function loop();
FUNCTION setup():
Step 1: set the pin mode for 13 as the output pin
Step 2: set the pin mode for pin 8 as input pin
Step 3: open the Serial port and set the data rate to 9600bps 
Step 4: while(!Serial)
print("Speed 0 to 255");
FUCTION loop()
Step 1: if (Serial.available()) input speed
Step 2 : if(Speed>=0 && speed<=255) set Speed
Step 3 : val= soil moisture Step 4 : if(val==LOW)
Confirmation from user and pass to motor Step 5 : else
Wait for 2mins gotostep1
 
 
### Features : Current hardware can Predict next cycle for irrigation automatically .

### Feasibility 

The biggest advantage of it this is a automatic system which only requires input of weather and it doesn't require human work-force. Also the cost of this advantage is minimal so it is practical and it can be used easily.


### Sustainability & Impact 
This project will help the on going problem. Also it will help to decrease the human work-force as it runs automatically.
