# Guild-Wars-Live-Split-Setup-Files

## Setup

TLDR Setup if you've never used live splits before.

Download Live splits and GW Live splits folder (Drop the runners setup/Exp Tracker folder into the Live splits components folder for less clicking later)

1.Launch Gw and launch live splits as admin.  (Do the instructions at LevelingUpLayout steps! if you are doing the lvl/LDOA/Survivor Tracker) then come back.
  
2.Load the default layout.(Right click the numbers that pop up-->load Layout-->From file--> 

<img width="154" height="33" alt="image" src="https://github.com/user-attachments/assets/7b1c8686-a467-4f76-803b-35e90ab9614f" /> or <img width="160" height="35" alt="image" src="https://github.com/user-attachments/assets/ff00f844-fb68-45b4-8808-ee127ab2e9d7" />. or setup your own.

3.Right Click Live splits-->edit layout-->click 

<img width="60" height="42" alt="image" src="https://github.com/user-attachments/assets/c5e7b1d5-d185-4e9c-a8e1-3a31953f1ecd" /> then <img width="364" height="75" alt="image" src="https://github.com/user-attachments/assets/efbd31c6-a2e9-4fc0-bc45-a590026f4974" />.

  Once you see 
  
  <img width="138" height="26" alt="image" src="https://github.com/user-attachments/assets/a8f06599-8ca7-4337-8315-c8cd2d6e5448" /> in the editor

4. CLick <img width="101" height="31" alt="image" src="https://github.com/user-attachments/assets/0cbc4215-a3ea-4523-bd2f-5ab1baee0ebd" /> then go to the tab <img width="131" height="23" alt="image" src="https://github.com/user-attachments/assets/7191efbd-db57-4b35-990a-6e3c98855188" />

   Browse-->to your .asl File

   <img width="534" height="135" alt="image" src="https://github.com/user-attachments/assets/f4886cff-866c-4292-ab77-80b044d82d83" /> or <img width="82" height="36" alt="image" src="https://github.com/user-attachments/assets/2e51c8d3-c3da-4df4-879a-c4b6fa075d4d" />

   Click OK twice to get back splits. RIGHT CLICK AND SAVE YOUR LAYOUT.

6. Right CLick -->(if you want any of the auto pause features to work ie laoding/town timer pause) otherwise skip
   
   <img width="354" height="132" alt="image" src="https://github.com/user-attachments/assets/85cd7176-4c66-4b41-855d-f4fb28ceb436" />


8. Now we load our splits or create your own. Select which ever one. <img width="386" height="58" alt="image" src="https://github.com/user-attachments/assets/ac47c2fa-cbcc-45b5-a345-c6f74ca7a709" />
  
9. Right click edit splits-->

  click activate-->settings or just click settings if activate is already greyed out 
  
  <img width="157" height="35" alt="image" src="https://github.com/user-attachments/assets/0dbadcfb-5a18-4bc2-8928-2c31b359ec38" /> or <img width="164" height="33" alt="image" src="https://github.com/user-attachments/assets/2a4b113c-33ec-4252-a420-bd92589e09e7" />

   Once again browse to your .ASL file 
   
   <img width="534" height="135" alt="image" src="https://github.com/user-attachments/assets/f4886cff-866c-4292-ab77-80b044d82d83" /> or <img width="82" height="36" alt="image" src="https://github.com/user-attachments/assets/2e51c8d3-c3da-4df4-879a-c4b6fa075d4d" />


   OK now we should see some settings pop in depending on which ASL file you chose.

   <img width="215" height="219" alt="image" src="https://github.com/user-attachments/assets/5e3131ef-564a-4249-9996-8220ff39a354" />  or <img width="298" height="119" alt="image" src="https://github.com/user-attachments/assets/b703cf2b-c9a8-4f1b-83db-a680fc7a7ca0" />


   **As a reminder you'll need to load the asl file for every new split you load**

   For runners you are basically done skip to the **Runners setting** to learn a little bit of how it works!

   For the EXP tracking go to **Adding extra information for EXP tracker**


## **LevelingUpLayout steps!**
  
Put 
<img width="195" height="35" alt="image" src="https://github.com/user-attachments/assets/2798eace-c7c3-46a0-9a58-43f0b031783e" />
(this is in the EXP Tracker Folder.)

into the Live Splits Component Folder
<img width="285" height="64" alt="image" src="https://github.com/user-attachments/assets/5d4f8adf-b753-4d26-a09b-10d20a43e93e" />


Once its in the folder, relaunch live splits. 

GO BACK TO TOP TO FINISH THE REGULAR SETUP!


## Adding extra information for EXP tracker(comeback Later)
iF YOU WISH TO SHOW SOME STATS ON THE TRACKER/splits. 
Then go back to edit layout. You'll now see this option to add to the editor.

<img width="610" height="128" alt="image" src="https://github.com/user-attachments/assets/33d053a6-e353-4ec4-9d01-fb2a306b91e5" />

Go to layout settings--> go to the new tab <img width="87" height="26" alt="image" src="https://github.com/user-attachments/assets/7841dd73-9223-4375-a184-9677aaef9d20" />
Label the section if you want/need and under value select what number you want to display! Status is a combo that shows current EXP and how much EXP to next milestone(based off your toggle!)
<img width="456" height="166" alt="image" src="https://github.com/user-attachments/assets/3fee50fa-2456-429e-a034-044bf88f3cc9" />

<img width="416" height="87" alt="image" src="https://github.com/user-attachments/assets/99d33812-7151-4a3d-be8c-29d2492afe26" />

**This cannot track any death that happens when the timer isn't running!

If the numbers are not updating remove it from the layout editor and re-add another ASLR viewer! (it can be finicky where if you have reload scripts sometimes it breaks)

This is just a Straight read of your Total EXP. 

I'm hoping to put in some manual overide (if people want it) to say start at this EXP* if anyone wants to just speed run the title from any level.**

## Runners Settings

**Reset on Death--> when you die it will pause the timer and then reset on any town visit.**
**Map-Base Auto Reset--> this will enable your choosen locations to auto reset the timer.**

Starts timer in any explorable.

Splits for every town and explorable.

Timer pauseses in town.
   

## EXP Tracker Settings

3 Modes of the Tracker

By Default ie (nothing else enabled). This will track 1-20. based off these values <img width="516" height="53" alt="image" src="https://github.com/user-attachments/assets/166cc93d-7eab-48d5-a055-b308bc24d04b" />
  
Use with <img width="122" height="41" alt="image" src="https://github.com/user-attachments/assets/591fd76e-0908-4506-bb12-422872bc85e3" /> or <img width="118" height="34" alt="image" src="https://github.com/user-attachments/assets/706f7fc3-14c9-4720-84c7-1c0a8397f460" />

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you enable Legendary Survivor  This move the goals to <img width="238" height="24" alt="image" src="https://github.com/user-attachments/assets/e4e35f97-064f-44c5-8f81-f4b546ff86f7" />

Use with <img width="174" height="30" alt="image" src="https://github.com/user-attachments/assets/ee43dd17-ce41-46fe-9509-ee5e02d1c3c9" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
If you Enable COMBO This will combine both to track 1-20/r1 survivor+r2+r3
Use with 

<img width="137" height="37" alt="image" src="https://github.com/user-attachments/assets/4d546c49-b944-4042-9ad7-adc694b3b3dc" /> and/or <img width="150" height="29" alt="image" src="https://github.com/user-attachments/assets/e46dae55-da5c-46cd-b790-ef1c6714f9ac" />





  

  












  


  
  
