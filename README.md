
# **AQUALERT**

AQUALERT is a compact electronic device which can accommodate any type of water bottle. The device will act as a platform for the bottle of the user to be kept on. It will take readings of the amount of water consumed by the user and offer reminders if the user forgets to drink the required amount of water inside a defined period of time.
# **PRODUCT BREAKDOWN**
## SYSTEM ARCHITECTURE 
<img src="Images/Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.005.png" id="fig:example" style="width:15cm"> 


## **POWER SUPPLY**
The power supply consists of TP4056 Lithium Battery Charging Module, which gets it power from USB input, a 1800mAh Li- ion battery and MT3608 DC-DC Step Up Boost convertor.

## **SENSORS**
The main component of the sensor module is a load cell with a capacity of up to 5kg. The sensor is used with a HX711 Dual-channel 24-bit AD Conversion Weighing Sensor Module. It senses the weight of the water bottle at given time intervals and send its’ inputs to the control unit.

## **INDICATORS**
There will be 2 main indicators used in AQUALERT. 

The first one will be a blinking LED indicator which will blink to remind the user to drink water.

The second indicator will be an OLED screen which will display reminder messages and the water consumed to the user. The screen used here is 128x32px. 

## **USER INTERFACE**
The user interface of the device mainly consists of 5 buttons. 

1. Power Switch to turn the device ON and OFF.
1. LED indicator switch.
1. Average water level up button
1. Average water level down button
1. Snooze button

## **CONTROL UNIT**
The control unit will consist of a microcontroller which will perform the vital calculations necessary for providing reminders on time. The microcontroller used is ATMEGA328P-PU DIP28.

# **ENCLOSURE DESIGN**
## INITIAL SKETCHES
# ![](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.006.jpeg)                                                    
##
##
##
##
## <a name="_hlk134355129"></a>SKETCHES OF THE FINALIZED DESIGN DRAWN USING SOFTWARE
![](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.007.png)![](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.008.png)

![](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.009.png)![A square device with a circular design

Description automatically generated]
# **BUILDING THE PROTOTYPE**
# TECHNICAL FEASIBILITY 
# We managed to find the key components required for the first prototype without much difficulty. The load cell, the ADC module, the charging module, the boost convertor module, the OLED screen and the microprocessor were sourced from local shops. 
# We created the basic load cell mounts using wood and connected it to a HX711 ADC and amplifier. The load cell and the OLED screen were connected to an Arduino UNO board. The Arduino board was used in place of the ATMEGA328P-PU DIP28 microcontroller for testing purposes.
# ![](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.011.jpeg)
The initially developed algorithm was used to create the code and it was run on the above system and tested successfully.

Hence it was deemed that our product was technically feasible with the resources available to us.

Furthermore, the initial Solidworks model for the enclosure and the initial PCB design was also designed. 



**Final Product**

As for the final product we have design the PCB using Altium and sent to JLC PCB in China to print the PCB. Enclosure was finalized using Solidworks and printed locally. After soldering the PCB and assembling all the component to the enclosure, we managed to deliver a working version of our product which is ready to enter the market.

![A close-up of a device

Description automatically generated](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.012.jpeg)![A square device with a circular design

Description automatically generated]![A black square device with a white circle on it

Description automatically generated](Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.014.jpeg)![A computer with a blue light on

Description automatically generated]





**MARKETING STRATEGY**

FINDING OUR WAY TO THE USER.   

**Market Description**

AQUALERT’s market consists of consumers and businesses who prefer to use a smart device to remind them to be hydrated regularly. Specific segments being targeted include professionals, corporations, students and medical users.

- Professionals: We are focusing on medium to high-income professionals who work from home or in personalized spaces.

  Ex: Software engineers, architects, entrepreneurs etc.

- Students: New generation of students and children especially focus on their health and well-being. We are trying to leverage this trend and provide them with a convenient way of managing their water consumption.
- Corporations: Companies with tight workspaces, and tight schedules, ex: Software companies, and nursing homes can use our product to elevate employee well-being.

Beyond these related market segments, we are planning to expand into **healthcare and medical services**. We believe that our product can be effectively used for **Dengue, Alzheimer’s and Dementia** management process which needs continuous hydration measurements. Our consumers will be local nursing homes, adult care centers and private hospitals with considerable budgets.

**Competitive Review**

- **WaterH**: A customised smart water bottle with a wireless charger and a reminder app. Beautifully designed and uses hydration and water quality sensors to provide feedback. Lacks the flexibility to allow users to use a bottle of their preference. The high price of Rs. 30000.00 is a competitive disadvantage in a middle-income consumer environment.
- **Hidrate Spark**: A beautifully designed water bottle with an iOS/Android app. Has find-my-bottle support and customizable reminders. Has only 4 designs and lacks flexibility. A high price margin of 69.00$ will become a disadvantage.
- **TabTime Droplet Hydration reminder**: A cup holder specifically designed for healthcare services. Designed to be used for Alzheimer's and Dementia management. Appearance is more functionality-based and less user-friendly. Has a low cost margin of 35.00$
- **ULLA**: A smart bottle attachment with a minimalist design. The small size of the product can be attractive to a wider audience. A low-cost margin of 25$ is an attractive offer to most upper-middle-income professionals. 

**Product Differentiation**

In a highly competitive environment, we have identified that it is crucial to differentiate ourselves from other products. We have planned to focus on the following details. 

- **Low price**: We are targeting a price-sensitive consumer environment. So we are focused on minimizing our production and marketing costs and creating enough space for price reduction and bonuses. 
- **Flexibility**: AQUALERT provides the flexibility to use any bottle ranging from small personal bottles to over 1.5-litre bottles. We are targeting to provide a number of unique designs from which consumers can choose.
- **Creative Design**: We have created AQUALERT to be matched to the office environment. Users can confidently use the product without distorting the surrounding.                             

**Distribution review**

Aqualert products will be distributed through a network of retailers and partners. We specially focus on the B2B strategy. Among the most important channel partners being contracted are:

- **Drinking water distributors**: Large providers of clean drinking water to major corporations can distribute AQUALERT as a part of their service supply. 

  *Ex: Speedy water, Mount Spring water*

- **Major electronic stores**: The consumer base of large electronic retailers can be used to market AQUALERT to upper-middle-income professionals. 

  *Ex: Abans, Singer*

- **Healthcare device providers**: We can add AQUALERT as an attractive healthcare solution to their portfolios.  



**BILL OF QUANTITIES**

`   `**Expenses for the items used so far**

|Item|Qty|Price **(**Rs)|
| :- | :- | :- |
||||
|**28 Pin DIP-28 SIP Round IC Sockets**|1|8\.00|
|**ATMEGA328-PU CHIP**|1|640\.00|
|**16MHz Oscillator quartz resonator**|1|14\.00|
|**10K resistor**|1|1\.00|
|**Blue LED 3mm**|10|10\.00|
|**Tactical Push button**|4|20\.00|
|**Switch**|2|40\.00|
|**0.1uF capacitor**|2|4\.00|
|**22pF capacitor**|2|4\.00|
|**Load cell 5kg**|2|4\.00|
|**HX711 A/D converter amplifier**|1|140\.00|
|**128x32 I2C OLED screen**|1|360\.00|
|**220Ohm resistor**|1|1\.00|
|**BC547 Transistor**|1|2\.00|
|**Diode 1N4001**|1|2\.00|
|**4.7K resistor**|4|4\.00|
|**Long 4-way PCB Mount Wire Clip**|3|120\.00|
|**Long 2-Way PCB Mount Wire Clip**|2|40\.00|
|**Enclosure 3D printing** |1|2500\.00|
|<p>**PCB** </p><p>**3.7V 1800mA Li-ion Rechargeable Battery**</p><p>**MT3608 DC-DC Boost Convertor**</p><p>**TP4056 Lithium Battery Charging Module**</p>|<p>1</p><p>1</p><p>1</p><p>1</p>|<p>`  `350.00</p><p>`  `600.00</p><p>` `280.00</p><p>` `160.00</p>|
|Total||**5304.00**|


**THE TEAM**

` `Task Delegation.

**Hewagamage K.L.N.**

- Coding and Soldering

**Abeywardana K.D.W.**

- Code debugging

**Edirisinghe E.A.D.D**

- PCB design and assembly

**Abeysinghe D.U.**

- Enclosure design
1**

[A computer with a blue light on

Description automatically generated]: Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.001.jpeg
[A square device with a circular design

Description automatically generated]: Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.010.jpeg
[A square device with a circular design

Description automatically generated]: Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.013.jpeg
[A computer with a blue light on

Description automatically generated]: Aspose.Words.be8777fe-dfb0-4368-ae32-3bad04579b88.015.jpeg
