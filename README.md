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

And here's the BOM from the website:
[BOM MsDb-1A3-JLCPCB Assembly Order (1).csv](https://github.com/user-attachments/files/26879597/BOM.MsDb-1A3-JLCPCB.Assembly.Order.1.csv)

Have a good one reviewing! My journal features a couple particularily humourous entries.

Update: fixed a capacitor footprint mismatch issue. Version 1A3 is the most current one, ready for review. Note that some files may or may not be mistakenly named as MsCp-XXX.
Update 2: Im really sorry for the mess this repository is. This UI is completely new to me, and I cant find the way to get all the files where I want them. When in doubt, always consult the latest versions.
