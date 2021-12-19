# UM-A Assembly Guide

## **Content of UM-A Kit**

<a href="img/UMA_Contents_2000px.jpg">
<img src="img/UMA_Contents_2000px.jpg" width="400">
</a>

**Housing** 
- 2 x Top Case
- 2 x Rear Cover
- 1 x Rotary Encoder Knob

**PCB**
- 1 x Left
- 1 x Right

**RF4 Plate**
- 1 x Left
- 1 x Right

**1 x OLED Screen PCB**

**1 x OLED Screen**

**2 x 4 Pins Sockets**

**1 x 4 Pins Cable**

**1 x Encoder**

**2 x TRRS PJ-320A**

**22 x M3 5mm screws** (Only 20 are required, rest are spare)

**10 x Rubber feet** (Only 8 are required, rest are spare)

---

## **Test the PCBs before soldering**

<a href="img/UMA_Asm_TestPCB.jpg">
<img src="img/UMA_Asm_TestPCB.jpg" width="400">
</a>


All PCBs are tested prior shipping, but it is good practice to make sure they are working before soldering. Both PCBs come pre-flashed Vial firmware, it should be recognised in Vial when connected to a computer. Plug in one half and test by shorting switch pins with tweezers. After testing one half, disconnect the first and test the other half. Don’t panic if the right side PCB outputs the wrong key for that switch location, as the firmware is set to left as master. As long as both halves produce some output you have verified the PCBs are working.

---

## **Assembling the Main PCBs**

## OLED Screen Connector
<a href="img/UMA_Asm_OLEDConnector_A.jpg">
<img src="img/UMA_Asm_OLEDConnector_A.jpg" width="400">
</a>

OLED screen connector is located on the left half.

<a href="img/UMA_Asm_OLEDConnector_B.jpg">
<img src="img/UMA_Asm_OLEDConnector_B.jpg" width="400">
</a>
<a href="img/UMA_Asm_OLEDConnector_C.jpg">
<img src="img/UMA_Asm_OLEDConnector_C.jpg" width="400">
</a>

Insert it on the underside of the PCB and then solder.


## TRRS Jacks
<a href="img/UMA_Asm_TRRS_A.jpg">
<img src="img/UMA_Asm_TRRS_A.jpg" width="400">
</a>
<a href="img/UMA_Asm_TRRS_B.jpg">
<img src="img/UMA_Asm_TRRS_B.jpg" width="400">
</a>

Place the jack on the underside of the PCB and solder.

## Encoder
<a href="img/UMA_Asm_Encoder_A.jpg">
<img src="img/UMA_Asm_Encoder_A.jpg" width="400">
</a>

Encoder is located on the right half.

<a href="img/UMA_Asm_Encoder_B.jpg">
<img src="img/UMA_Asm_Encoder_B.jpg" width="400">
</a>
<a href="img/UMA_Asm_Encoder_C.jpg">
<img src="img/UMA_Asm_Encoder_C.jpg" width="400">
</a>

Insert encoder to the front of the PCB, solder it from the underside of the PCB.

## Stabilisers

<a href="img/UMA_Asm_Stab_A.jpg">
<img src="img/UMA_Asm_Stab_A.jpg" width="400">
</a>
<br>
<a href="img/UMA_Asm_Stab_B.jpg">
<img src="img/UMA_Asm_Stab_B.jpg" width="400">
</a>
<a href="img/UMA_Asm_Stab_C.jpg">
<img src="img/UMA_Asm_Stab_C.jpg" width="400">
</a>

When installing screw-in stabiliser for Spacekey on the left half, use a washer/electrical tape to isolate the screw and the LED contacts to prevent shorting.

## Select PCB Layout before solding switches
<a href="img/UMA_Asm_Layout_L.jpg">
<img src="img/UMA_Asm_Layout_L.jpg" width="400">
</a>

<a href="img/UMA_Asm_Layout_R.jpg">
<img src="img/UMA_Asm_Layout_R.jpg" width="400">
</a>

Select one layout when soldering switches. Then insert switches to the plates and solder to the PCBs.


## Soldering switches

<iframe
    width="640"
    height="480"
    src="https://www.youtube.com/embed/JpV-eJNrXjk"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Solder switches as you normally would with other keyboards.
Here is a good tutorial by JUJU.

## LED
<a href="img/UMA_Asm_LED.jpg">
<img src="img/UMA_Asm_LED.jpg" width="400">
</a>

Round pad: Anode (+)

Square pad: Cathode (-)

---

## **Soldering OLED screen PCB**

<a href="img/15_OLED_PCB.jpg">
<img src="img/15_OLED_PCB.jpg" width="400">
</a>

Note the front and back of the PCB

<a href="img/16_OLED_Conn_A.jpg">
<img src="img/16_OLED_Conn_A.jpg" width="400">
</a>
<a href="img/16_OLED_Conn_B.jpg">
<img src="img/16_OLED_Conn_B.jpg" width="400">
</a>

Insert the 4 pin connector to the back of the PCB. Align it with the marking on the PCB and then solder each pin from the front.

### **Be sure to solder correctly in this step, as there will be no access to the solder joints once the OLED screen is in place.**

<a href="img/OLEDScreen_A.jpg">
<img src="img/OLEDScreen_A.jpg" width="400">
</a>
<a href="img/OLEDScreen_B.jpg">
<img src="img/OLEDScreen_B.jpg" width="400">
</a>

Insert the short pins of the OLED screen header through the back of the OLED PCB then solder from the front. Then place the long pins of the screen header through the black mounting PCB and solder each pin from the underside.

<a href="img/17_OLED_Trim_A.jpg">
<img src="img/17_OLED_Trim_A.jpg" width="400">
</a>
<a href="img/17_OLED_Trim_B.jpg">
<img src="img/17_OLED_Trim_B.jpg" width="400">
</a>

Trim header pins short on both side. 

<a href="img/17_OLED_Trim_C.jpg">
<img src="img/17_OLED_Trim_C.jpg" width="400">
</a>
<a href="img/OLED_Tilt.jpg">
<img src="img/OLED_Tilt.jpg" width="400">
</a>

Be sure the pins on the front are not protruding higher than the screen. Also, tilt-up the OLED screen slightly. Otherwise, there will be a gap between the case and the screen.


<a href="img/UMA_Asm_OLEDInstall_A.jpg">
<img src="img/UMA_Asm_OLEDInstall_A.jpg" width="400">
</a>
<a href="img/UMA_Asm_OLEDInstall_B.jpg">
<img src="img/UMA_Asm_OLEDInstall_B.jpg" width="400">
</a>

Attached the OLED screen to the left case with 2 M3 5mm screws.


## **Mount PCB assembly to case**

<a href="img/UMA_Asm_CaseInstall_A.jpg">
<img src="img/UMA_Asm_CaseInstall_A.jpg" width="400">
</a>
<a href="img/UMA_Asm_CaseInstall_B.jpg">
<img src="img/UMA_Asm_CaseInstall_B.jpg" width="400">
</a>

There are 5 mounting points on each side. Secure the PCB with the M3 5mm screws.

## **Connecting OLED screen**

<a href="img/UMA_Asm_OLEDCable.jpg">
<img src="img/UMA_Asm_OLEDCable.jpg" width="400">
</a>

Connect OLED screen with the 4 pin cable.

## **Case Assembly**

<a href="img/UMA_Asm_Cover.jpg">
<img src="img/UMA_Asm_Cover.jpg" width="400">
</a>

Place the cover onto the case, fasten them with M3 5mm screws. Stick the rubber feet on and it’s done!

---

<a href="img/UMA_Mint_43.jpg">
<img src="img/UMA_Mint_43.jpg" width="600">
</a>

---