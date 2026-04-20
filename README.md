Hey there, fellow human!
I'm a portuguese 17 year old highschooler with aspirations of getting into aerospacial engineering one day. And since I know how important it is to start building experience
early, I decided to try out a hackclub starter project. And what an undertaking this was. I picked the "Design a custom PCB" thinking it couldnt be THAT hard. Yeah
no, hard would be the understatement of the century. I had hardly ever touched a CAD program in my life, and KiCAD looked like it'd have a very sharp looking skill curve.
As it did indeed. But I presevered. Despite me relentlessly complaining about you guys' tutorial, I have to admit it was essential to me completing this, and it sure forced me
to learn a lot at times when it did not hold my hand through some of the ins and outs of PCB building. I love every bit that led me to completing my first ever PCB,
hopefully of more to come!

I'm also not particularily handy with GitHub, I've honestly always found the UI to be quite intimidating. I think I satisfy your admission requirements, but I wouldnt 
put it above me to miss something fulcral completely. 

The board is named after my own versioning system. Ms are my initials, Db stands for DevBoard, the first 1 is the major version count, the A is the major branch count, and the
final number is the revision count.

I spent way longer than anticipated, partly due to some complications that occured while trying to find the smaller flash storage and LDO that the tutorial used, that led
me to quite the quagmire in trying to fit much larger components in a board with nearly the same footprint. Though that led me to a design that implemented a whoping
16MB of flash storage, some 8x more than the Raspberry Pi Pico. And an LDO capable of drawing more current. So yeah here's that as a unique factor LOL.


ChatGPT did me a solid on this one. If you're interested in seeing an LLM teach the equivalent of a foulmouthed juvenile chimpanzee how PCB's work, here's our full conversation: https://chatgpt.com/share/69e56555-d1f8-83eb-b878-137e63521a72
And don't worry, the most "AI" that was actually _directly_ inolved in the making of this project was the DRC rules checker. 
By the way, I doubt this counts as a complexity 3 project simply due to the hour count. But hey it can't hurt to ask right?


Anyhow, here's some eye candy for your troubles of  reading this:
<img width="1919" height="1079" alt="Screenshot 2026-04-19 185134" src="https://github.com/user-attachments/assets/74f4ee98-fc99-492a-a66a-f6acf8d9b62e" />
<img width="256" height="574" alt="image" src="https://github.com/user-attachments/assets/50e3f172-bb21-4150-93af-4e7fc5ef0ddf" />
<img width="627" height="428" alt="image" src="https://github.com/user-attachments/assets/78498623-64d0-4b2d-9353-6c505533d0ae" />

And here's the BOM as a raw CSV: 


"Reference","Qty","Value","DNP","Exclude from BOM","Exclude from Board","Footprint","Datasheet","#"
"12MHz1","1","Crystal_GND24","","","","Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm","","1"
"C1,C2","2","10uF","","","","Capacitor_SMD:C_0603_1608Metric","","2"
"C3,C22","2","33pF","","","","Capacitor_SMD:C_0402_1005Metric_Pad0.74x0.62mm_HandSolder","","3"
"C5,C7,C8,C9,C10,C11,C12,C13,C14,C16,C17","11","0.1uF","","","","Capacitor_SMD:C_0402_1005Metric_Pad0.74x0.62mm_HandSolder","","4"
"C6,C15","2","1uF","","","","Capacitor_SMD:C_0402_1005Metric_Pad0.74x0.62mm_HandSolder","","5"
"J1","1","USB_C_Receptacle_USB2.0_14P","","","","Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12","https://www.usb.org/sites/default/files/documents/usb_type-c.zip","6"
"J2,J3","2","Conn_01x20","","","","Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical","","7"
"J4","1","Conn_01x03","","","","Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical","","8"
"R1,R2","2","27","","","","Resistor_SMD:R_0402_1005Metric","","9"
"R3","1","5.1K","","","","Resistor_SMD:R_0402_1005Metric","","10"
"R5,R7","2","1K","","","","Resistor_SMD:R_0402_1005Metric","","11"
"R6","1","10k","","","","Resistor_SMD:R_0402_1005Metric","","12"
"R51","1","5.1K","","","","Resistor_SMD:R_0402_1005Metric_Pad0.72x0.64mm_HandSolder","","13"
"SW1","1","SW_Push","","","","Button_Switch_SMD:SW_SPST_TS-1088-xR020","","14"
"U1","1","RP2040","","","","Package_DFN_QFN:QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm","https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf","15"
"U2","1","NCP1117-3.3_SOT223","","","","Package_TO_SOT_SMD:SOT-223-3_TabPin2","http://www.onsemi.com/pub_link/Collateral/NCP1117-D.PDF","16"
"U3","1","W25Q128JVS","","","","Package_SO:SOIC-8_5.3x5.3mm_P1.27mm","https://www.winbond.com/resource-files/w25q128jv_dtr%20revc%2003272018%20plus.pdf","17"

Have a good one reviewing! My journal features a couple particularily humourous entries.

Update: fixed a capacitor footprint mismatch issue. Version 1A3 is the most current one, ready for review. Note that some files may or may not be mistakenly named as MsCp-XXX.
