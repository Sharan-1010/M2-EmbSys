 # Automated Hand Sanitizing System
 ## Table Of Contents
 |S. No|Contents|
 |--|--|
 |1.|Automated Hand Sanitizing System|
 |1.1|Abstract|
 |1.2|Features|
 |1.3|SWOT analysis|
 |1.4|4W's and 1H|
 |2.|Requirements|
 |2.1|High Level Requirements|
 |2.2|Low Level Requirements|
 |3.|Block Diagram and Explanation|
 |3.1|Block Diagram|
 |3.2|Explanation|
 |4.|Architecture|
 |4.1|Behavioural Diagram|
 |4.2|Structural Diagram|
 |5.|Testplan and Output|
 |5.1|High Level Testplan|
 |5.2|Low Level Testplan|
 |6.|Applications|
 ---
 ## 1. Automated Hand Sanitizing System
 ## 1.1.  Abstract:
 This project implements automatic hand sanitizer for preventing bacteria's and germ's present in the hands before entering a building. Hands are considered to be the primary mode of infectious diseases, especially for those living in close proximity such as college residence halls, shopping malls, bank halls, market areas etc. Because of the frequent contact with hands and multiple surfaces, the incidence of cross-contamination is significantly increased, with this project the contamination of disease is reduced and prevented. This system does not the person without using the hand washer. The hand washer contains sanitizer which prevents most of the germs present in hands. This system is connected with the door of the entrance with electromagnetic lock which locks and open the door with the help of servo motor.
 ## 1.2. Features:
 

 - This system uses ultrasonic sensor that senses the hand of a person and pours the sanitizer.
 - The people who enters the building will not be allowed without sanitizing their hands.
 - This projects assists in avoiding the contamination of germs.
 - This project uses electromagnetic lock to lock the door in the entrance of the building.
 - This system has a LCD display which displays the door status.

##  1.3. SWOT Analysis:
## SWOT Analysis:

## Strength:
1.Requires less time to wash the hands.
2.  Does not allow anyone without sanitizing the hands.
3.  Reduces the risk of getting affected to germs.

##  Weakness:
1.  Needs power supply frequently.
2.  Usage of water may increase.
3.  Water may affect the circuit.

## Opportunities:

1.  They have greater accuracy than any other methods of sanitizing the hands.
2.  Ultrasonic sensors are easy to use and not harm to anyone.
3.  This system can be used any buildings to avoid germs and diseases.

##  Threats:

1.  Limited testing distance of hands.
2.  Inflexible scanning methods.
3.  The system may get damaged to water.
___
## 1.4. 4W's and 1H:
## Who:

For peoples who goes to many places.

## Where:

For buildings and places where lots of people.

## What:

Auto touchless handwashing timer.

## When:

Every where, where there is a need for prevention of diseases.

## How:

This system is automated and controlled automatically.
 
 
 ## 2. Requirements:
 ## 2.1. High Level Requirements:
|S. NO| Description| Status|
|-- |-- |--|
|HLR1|ATMEGA 328|Implemented|
|HLR2|Ultrasonic Sensor| Implemented|
___
## 2.2.  Low Level Requirements:
|S. No| Description | Status |
|--|--|--|
|LLR1|LCD Display| Implemented|
|LLR2|LED Light |Implemented|
|LLR3|Electromagnetic Lock| Implemented|
## 3. Block Diagram and Explanation:
## 3.1. Block Diagram:
![AHW block diagram](https://user-images.githubusercontent.com/82869478/154842531-33111d06-9db2-41df-b88f-28ac3945d3fd.jpg)
## Explanation:
# Components Discription:
## Atmega 328:
  It is the controlling device of the system. It controls the components interfaced with the device.
  ##  Battery:
  It supplies the power supply to the system.
  ##  Voltage Regulator:
  It is used maintain constant volatge to the controller and motors.
  ## Electromagnetic Lock:
It is used to locks the door and the tap.
## Ultrasonic Sensor:
It is used to sense the hands when placed under the tap.
## Servo Motor:
It is used to pour the sanitizer on the hands and open and close the doors.
## LED Lights:
It is used for indicating purpose.
## LCD Display:
It is used to display the output that is "The entrance door is open".
## 4.Architecture:
## 4.1. Behavioural Diagram:
![M2-Behavioural Diagram](https://user-images.githubusercontent.com/82869478/157168475-08ab39f5-7995-48fb-a5c9-fbc7782c8e24.png)
## 4.2. Structural Diagram:
![M2-Structural diagram](https://user-images.githubusercontent.com/82869478/157168682-9b4a752e-8ec4-4976-92c6-fecacd57022a.jpg)
## 5. Testplan and Output:
## 5.1. High Level Test Plan:
|Test ID | Description| Expected O/P| Actual O/P  | Type of Test |
|-- |-- |--|--|--|
|HLT1| Sensing Human Hands |Sensing |Success |Requirement Based|
|HLT2|Sanitizing Hands |Sanitizing |Success |Scenario based|
|HLT3|Delay OFF |Running | Success |Boundary based|
___
## 5.2. Low Level Test Plan:
|Test ID | Description| Expected O/P| Actual O/P  | Type of Test |
|-- |-- |--|--|--|
|LLT1|Identify and Sense Object| Sensed| Success| Requirement Based|
|LLT2| Display| Processing | Success| Scenario Based|
|LLT3 |Auto Off | Done| Success| Boundary Based|

## 6. Applications:
 - This system can be used in public and private buildings  such as hospital, mall, home...
 - This system is used in conjunction with automatic faucets in public restrooms.
 - This system  helps conserve the amount of sanitizer used and stem infectious disease transmission.
 - During the time of COVID-19, it is one of the most needed product for humankind.
 - This system avoids the contamination without spreading. 



 ## Project Done By:
   |PS NO.|NAME|
   |--|--|
   |99007629|Udhaya Sharan B|

