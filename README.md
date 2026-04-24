Hey there, fellow human!
I'm a portuguese 17 year old highschooler with aspirations of getting into aerospacial engineering one day. And since I know how important it is to start building experience
early, I decided to try out a hackclub starter project. And what an undertaking this was. I picked the "Design a custom PCB" thinking it couldnt be THAT hard. Yeah
no, hard would be the understatement of the century. I had hardly ever touched a CAD program in my life, and KiCAD looked like it'd have a very sharp looking skill curve.
As it did indeed. But I presevered. Despite me relentlessly complaining about you guys' tutorial, I have to admit it was essential to me completing this, and it sure forced me
to learn a lot at times when it did not hold my hand through some of the ins and outs of PCB building. I love every bit that led me to completing my first ever PCB,
hopefully of more to come!

I'm also not particularily handy with GitHub, I've honestly always found the UI to be quite intimidating. I think I satisfy your admission requirements, but I wouldnt put it above me to miss something fulcral completely. 

The board is named after my own versioning system. Ms are my initials, Db stands for DevBoard, the first 1 is the major version count, the A is the major branch count, and the final number is the revision count.

I spent way longer than anticipated, partly due to some complications that occured while trying to find the smaller flash storage and LDO that the tutorial used, that led me to quite the quagmire in trying to fit much larger components in a board with nearly the same footprint. Though that led me to a design that implemented a whoping 16MB of flash storage, some 8x more than the Raspberry Pi Pico. And an LDO capable of drawing more current. So yeah here's that as a unique factor LOL.


ChatGPT did me a solid on this one. If you're interested in seeing an LLM teach the equivalent of a foulmouthed juvenile chimpanzee how PCB's work, here's our full conversation: https://chatgpt.com/share/69e56555-d1f8-83eb-b878-137e63521a72
And don't worry, the most "AI" that was actually _directly_ inolved in the making of this project was the DRC rules checker. 


Anyhow, here's some eye candy for your troubles of  reading this:
<img width="1919" height="1079" alt="Screenshot 2026-04-19 185134" src="https://github.com/user-attachments/assets/74f4ee98-fc99-492a-a66a-f6acf8d9b62e" />
<img width="256" height="574" alt="image" src="https://github.com/user-attachments/assets/50e3f172-bb21-4150-93af-4e7fc5ef0ddf" />
<img width="1022" height="643" alt="image" src="https://github.com/user-attachments/assets/5ae3b076-bb8f-417b-850c-7c1d8cdcdec4" />


And here's the BOM from the website:
[BOM MsDb-1A3-JLCPCB Assembly Order (1).csv](https://github.com/user-attachments/files/26879597/BOM.MsDb-1A3-JLCPCB.Assembly.Order.1.csv)

Have a good one reviewing! My journal features a couple particularily humourous entries.

Update: fixed a capacitor footprint mismatch issue. Version 1A3 is the most current one, ready for review. Note that some files may or may not be mistakenly named as MsCp-XXX.

Update 2: Im really sorry for the mess this repository is. This UI is completely new to me, and I cant find the way to get all the files where I want them. When in doubt, always consult the latest versions.

-----------------------------------------------------------------------------------------------------------------
IMPORTANT:

Update 3: Looking back, I can see that some of my wording contrasts quite sharply with my actual broader feelings for hackclub's cause, so I feel the need to clarify a bit.

I believe I should have kept it a bit more mature in the journal. Though it was humourous to read some of the entries I had left, many were made the way they were for exactly the purpose of being funny, something which I honestly regard as a mistake. Some things were taken out of proportion in a place where I feel like things should have been a bit more grounded, and especially for a reviewer who does not know me at all, I see how they might be taken as me not taking the project seriously. I took the generally casual wording of your website and ran with it way too far. My mistake for that.

For being a complexity 2 project, the tutorial likely assumed some previous experience in the field, something which I, who simply picked the most interesting starter project regardless of complexity, failed to account for.
Hence the need for so many explanations, hence the frustration. And, considering my exaustion for working non stop for days, the chaotic formatting and tone. 

I'm writing this now in a much clearer headspace, and while I am not exactly catastrophizing this, I do feel like I didn't pay the respect I should have, especially to the tutorial, and that deserves an apology. 

ChaGPT acted here as a consultant, which is another point I'd like to emphasize, because I did convey this rather badly both in the journal and in my previous paragraph. What I meant by it not being "directly involved" was specifically it not being a direct agent or a decision-taker, having served solely for the purpose of research, counseling, and honestly venting. The way I framed it against the DRC was wrong, as they actually both served similar purposes, to sanity check. 

Also, me thinking the project could be counted as tier 3 was a bit silly. Me being new to this and having struggled with it doesnt warrant a higher complexity rating. 

I hope the last entry I submitted in the journal at the time of sumbittal now sounds a bit less out of character. Truth is that it is my character, and my level-headed feelings toward the organization. Something which I had previously failed to convey amidst my frustration and my desire to be funny to myself.

That said, while I do regret a couple things, I'll take it in stride and strive to be better. You live and you learn, and I can safely say that this was a huge learning experience, both in KiCAD and in how I should address things in records. 

Have a good day, and thank you for the work you're putting in for this foundation.



