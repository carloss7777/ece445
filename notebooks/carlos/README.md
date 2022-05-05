# ECE 445 Team 12
## Machine Shop Meeting (02/01/2022):
This was our first meeting with Greg. He gave us some feedback of our porject and he told us what kind of servomotor would be the best to control the angle of the laser.
## TA Meeting (02/08/2022):
In the first meeting with the TA, we solved our initial doubts. They were the following:

  - How to design our PCB and can we use arduino? The answer was that we have to design our PCB wich will be very similar to the one in the CAD assigment
  
  - Which are our firsts steps?  The recommendation of our TA was starting by the more specific pieces of our project and after starting to escaleto back to the microprocessor.
  
  - What kind of microprocessor do we need? We need one that is compatible with all of our elements.
## Soldering Assigment #1 (02/18/2022):
For the soldering assigment I went to the lab with my peers and I finished all the soldering stuff but I will have to finish the rest next week because the TA left before I can upload the code to my PCB.
## Team Meeting #1 (02/19/2022):
Today it was our first meeting. We have been fixing our proposal, correcting all the errors that we made and we resubmitted it. We have decided that tomorrow we will be meeting to work on the Design Document.  
## Team Meeting #2 (02/20/2022):
Today we have worked on our Design Document, finishing all the parts and we also decided wich part will present in the DDC. 
## DDC Review (02/21/2022):
Today we had the DDC review with professor Schuh, TAs and some peers. They give us some feedback about our project and told us some changes that we should do, this changes are the following:
- First of all, we have to rewrite one of ours high-level requierments because we didn't specified with exact numbers the increment or decrement of the target pace every time we press the buttons.
- Talknig about the block diagram, they told us that we need to specify wich is the voltage that needs every component and wich kind of protocol we will be using in order to communicate between components. Furthermore, we should remove the specific components that we use from our block diagram.
- For the RV tables, we have to change a bit our format and we should add tolerance to the resistors.
- For the tolerance analysis, we have to change the approach in order to be more specific.
- Lastly, for our ethics and safety, we should change the ethics and add ethical issues like privacy, security...
## Soldering Assigment #2 (02/21/2022):
Just after finishing our DDC review we went to the senior lab, and I could finish my soldering assigment this same day after updating the code to my PCB and assembly all the components.
## Meeting with TA (02/23/2022):
Today we have met with our TA Daniel in order to doing the last check to our Design Document. He gave us some feedback of what we should improve, the main changes that we need to do are:
- Fixing formatting issues
- Changing how we write the verifications in the RV tables. We need to be more specific on that.
- We shoud add numbers to our high-level requirments.
## Meeting before Design Document Review (02/28/2022):
On our weekly meeting with Daniel we have discussed some key aspects of our project:
  1. Daniel made a quick check on our PCB and he helped us with one step that we were stucked.
  2. We talked about the parts that we should order.
  3. We made the last review of our Design Document and he told us how was the best way to present it.
## Design Review (03/01/2022):
Today we have presented our Design Document to professor Schuh, our TA Daniel and two TAs more. We have recived the following feedback:
- One TA was concerned about the battery weight. We definetaly will have to be aware.
- Professor Schuh made a good point on the refreshing time of the servomotor position. He recommended us to set a refreshing time of 3s to avoid any problem.
- We also have to put a reference to see which is the point from where we are measuring the angle
- On the formatting aspect, we should put the table titles before the table and the images titles just below.
- Finally, one TA made a point on the toleerance used to power the microcontroller, since if we fall below some voltage the MCU can have problems.
## Laser Test (03/01/2022):
Right after the Design Review, we went with Daniel to check our potential laser and we saw that we should look for another that is more visible.
## PCB Board Review (03/01/2022):
We went to the PCB board review in order to solve our doubts with it and also we checked with the TAs that there weren't any visible errors on the design.
## Team Meeting with TA to complete PCB and DDC (03/05/2022):
Today we have met with Daniel via Zoom, to discuss about our DDC and make the lasts changes before submitting it. We also talked briefly about the PCB and Daniel solved our concerns about it. 
## Order Parts 1 (03/05/2022):
We have made our first order of parts
## General TA meeting (03/07/2022):
We had a last minute problem with our MCU since it run out of stock and we have to change the PCB inmediately for submitting it tomorrow. Daniel helped us finding a similar MCU to substitute our previous one and we decided to use the ATMega809.
## PCB Order 1 (03/08/2022):
Today we have finished to re-do the PCB with our new MCU and I send the Gerber Files to Daniel. 
## Teamwork Evaluation (03/09/2022):
We have completed the teamwork evaluation individually.
## SPRING BREAK (03/11/2022 - 03/20/2022):
During Spring we didn't work on the project, but we recived the notice that our parts deliver was rejected.
## First Team Meeting After SP Break (03/23/2022):
In the team meeting that we had today, we have checked what went wrong with our parts order. 
Furthermore, we spent some time looking for a laser and we made a call to an expert in lasers to get some extra advice.
## General TA Meting (03/25/2022):
Since our parts haven't arrived we were worried about what we could do while we were waiting for them since we had planned to have already soldered the PCB. We decided to start with the GPS code. We also get some capacitors and resistors from the lab.
## Parts Ordering #2 (03/28/2022):
Today we had another inconvenient with the parts, our package was lost and we have met to re-order again everything. 
## GPS Code (03/30/2022):
Today, as planned we have started to do the code necessary for getting the GPS data and we talked about which were the following steps that we are going to take. We made important progress on the GPS code.
## Laser Testing and Lab Notebook (03/31/2022):
Today we met because our laser arrived this morning. We have tested the laser and it seems to work properly and is visible even if there is a sunny day.
We also worked on our Lab Notebooks, updating all the work we have done during the previous weeks.
## Meeting with Daniel (04/01/2022):
We discuss with our TA the progress and we talk about the PCB design and coding.
## Picking up parts(04/05/2022):
Today arrived the parts of our project, we tested initially some of the components in the breadboard and verified they were working.
## Start Soldering (04/07/2022):
We started by soldering the microcontroller with the microscope, and we also soldered the other parts except for the GPS Module, since it didnt arrived.
## Picking up parts 2 (04/09/2022):
There was a second deliver of our parts. As we did in the first time, we noticed that we were missing the crystal so we ordered a new one.
## Testing day (04/11/2022):
Today we've tested some subsystems. To do that we built the circuits on the breadboard and we did our R&V tables of the subsystem.
## Flashing problem (04/12/2022):
We tried to  flash our microcontroller, but we discovered that we couldn't do it with USB ASP, since they weren't compatible.
## Flashing problem #2 (4/13/2022):
Today we've tried to solve the problem of flashing the MCU but we realized that the UART pin neccesary for programming the PCB. We decided to move to an ATMega328p  and we order an arduino nano to grab the MCU from it.
## Flashing problem #3 (04/14/2022):
We changed the PCB to implement our new MCU. 
## Order PCB round #3 (04/15/2022):
We ordered the new PCB, and we did the R&V table for the buttons.
## Breadboard circuit to flash the ATMega (04/17/2022):
Today,we build on the breadboard the circuit to flash the ATMega with an Arduino UNO. We didn't flash it today because we had some issues.
## Flashing the ATMega (04/18/2022):
We solve the problem that we had yesterday and we managed to flash the ATMega.
## Testing day #2 (04/19/2022):
We tested all the subsystems with the ATMega328p in the breadboard.
## Mock DEMO (04/20/2022):
We show our progress to the TA.
## PCB round #3 arrives (04/21/2022):
Today we spent the whole day soldering and checking the correct working of our PCB. Once we had it, we flash our PCB and we programmed it.
## Test LCD on PCB (04/22/2022):
We connected the LCD to the PCB, we had some problems but they were solved on the same day. We started to work on the buttons.
## 
