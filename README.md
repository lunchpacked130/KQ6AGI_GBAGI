# Kings Quest VI AGI DeMake Gameboy Advance port Readme.

## Index
● [What](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#what) is this github about?

● [Why](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#why) make this github?

● [How](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#how) do I use GBAGI to convert AGI games to GameBoy Advance rom?

● [Where](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#where) can i find downloads and links?

● [HUH](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#huh) Helpful Useful Hints if I get stuck (with no spoilers unless i choose to reveal them)

● [Disclaimers](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#disclaimers)

### What is this Github about?

This is a GameBoy Advance rom of Kings Quest VI AGI DeMake i created using GBAGI.
I decided to share the rom here in case anyone else would like to try it out and/or play this amazing creation on the go on your GBA.

> [!NOTE]
> This rom works on:
>  
> ● GBA Software Emulators
> 
> ● Fpga GBA Hardware cores
> 
> ● Real GBA Hardware. (Requires flashcart)

> [!NOTE]
> GBAGI is **ONLY** available for Windows

I've only tested playing through the Long route, but the game should be 100% completable in any way you want.


### Why make this github?

A little while back, I discovered Brian Provinciano's GBAGI which could port AGI games to be playable on GameBoy Advance, and found it intriguing, even though GBAGI was last updated 20 years ago in 2004, it still worked on modern windows.
But since i never really got into playing text-parser adventure games, (even though there's menus with words instead of a text parser) and GBAGI was having some issues, like sound channels not being synced etc. As well as some game-stopping bugs like being unable to close a door you need closed to progress, i never got around to actually really play any of the ports, and I more or less wrote it off as just a novelty.

Then about a month ago at the time of writing this, several things started to happen;

Brandon Kouri released his 18-years-in-the-making amazing AGI DeMake of one of my all time favourite games;  Kings Quest VI.

Space Quest Historian made a video about GBAGI and played through Space Quest 1 & 2 using a GBA emulator.
<details> 
<summary> Watch SQH's Videos here: </summary>

**Space Quest... on the Game Boy Advance?!**
[![Space Quest... on the Game Boy Advance?!](https://img.youtube.com/vi/ZN0FByl1bos/0.jpg)](https://www.youtube.com/watch?v=ZN0FByl1bos)

**Space Quest I: The Sarien Encounter - Game Boy Advance - Full playthrough:**
[![Space Quest I: The Sarien Encounter - Game Boy Advance - Full playthrough](https://img.youtube.com/vi/ofoLtr4MbzY/0.jpg)](https://www.youtube.com/watch?v=ofoLtr4MbzY)

**Space Quest II: Vohaul's Revenge - Game Boy Advance - Full playthrough:**
[![Space Quest II: Vohaul's Revenge - Game Boy Advance - Full playthrough](https://img.youtube.com/vi/AUbRSzzcg9Y/0.jpg)](https://www.youtube.com/watch?v=AUbRSzzcg9Y)
</details>

During SQHs playthrough of the GBAGI port of Space Quest 1, he discovered a progress breaking bug, but managed to work around it. 

This made Davidebyzero look deeper into how GBAGI worked and started updating it and fixing all the issues like audio and the progress breaking bug in SQ1 etc. And after 20 years since the last update, GBAGI now got new updates and fixes.

So in the end, curiosity got the better of me, and i ported KQ6AGI with GBAGI and played through the entire game (Long path) and strangely, the more i played, the more it kept growing on me.

<details> 
<summary> Watch my full playthrough of KQ6AGI on GBA here.</summary>

**King's Quest VI AGI DeMake GameBoy Advance Port Full Playthrough (No Commentary)**

[![King's Quest VI AGI DeMake GameBoy Advance Port Full Playthrough (No Commentary)](https://img.youtube.com/vi/-qFwTzw5qf8/0.jpg)](https://www.youtube.com/watch?v=-qFwTzw5qf8)
</details> 

It's not only a love letter to the original Kings Quest VI, but also such an incredible achievement to recreate all of Kings Quest VI in the AGI engine in such detail.

### How do I use GBAGI to convert AGI games to GameBoy Advance rom?

If you'd rather make your own rom, or convert some other AGI games from your collection, just follow this simple guide.
(Images are from a previous version, but the layout is identical.

First you'll need the game files for the AGI game you want to port and GBAGI.
For this guide I'm using KQ6AGI, but any AGI game should potentially work. 
The procedure is identical for all AGI games

> [!IMPORTANT]
> GBAGI is Windows only (Sorry)

**1) downloads and preparations**

[Download GBAGI from here](https://github.com/Davidebyzero/GBAGI)

[OPTIONAL! Download KQ6AGI DeMake from here](https://kq6agi.com) 

> [!NOTE]
> KQ6AGI is only needed if you want to play King's Quest VI AGI DeMake. 

> [!TIP]
> I've added a [list of Official Sierra AGI engine games](https://github.com/lunchpacked130/KQ6AGI_GBAGI/edit/main/README.md#list-of-official-sierra-agi-games) section further down with links to GOG.com where you can purchase some of the games.

> [!TIP]
> I have also provided links to 5 Sierra AGI demo packs in the ** Downloads ** section further down.

> [!NOTE]
> You will have to provide any other AGI games yourself.


**2) Extracting and getting things ready.**

![files](https://github.com/user-attachments/assets/c7ec8de9-e2ec-4e2a-af3a-1527f48b83cb)

Extract the contents of gbagi-bin-2.××.zip (or the most recent release) to its own folder, then
Extract or copy the AGI games you want to port to GBA to their own subfolders within the folder.

> [!NOTE]
> You dont *have* to do this, but it's a good way to keep things simple, clean and safe, and i prefer working with copies instead of my original files "just in case"

**3) Starting the GBAGI porting tool**

In the GBAGI folder, start "gbinject.exe"

**4) Adding Games**

![Adding Games](https://github.com/user-attachments/assets/1fa8b98d-c944-4f03-8f2e-2c4df364e8c5)

![Selecting Games](https://github.com/user-attachments/assets/e3453376-824f-4e46-af4e-0fc29b2d5a26)

Select [Add Game] (D) and navigate to the root folder of the AGI game you want to add

> [!CAUTION]
> Don't touch fields (A) and (B) unless you know what you're doing.
In field (C) you can edit the path and rom filename to your liking.
pressing **[Browse...]** let's you easily select another location and filename to save the GBA rom file
(Default name and location is "agigames.gba" located in the same folder as gbinject.exe)
 
**5) Settings and Names**

![4 game settings](https://github.com/user-attachments/assets/ff4690c5-02f0-4cec-8be8-8e9433eb5d0d)

GBAGI should detect the settings automatically so you should not have to touch anything here, just press **OK**

> [!NOTE]
> The names from step 5 is used for the menu entry.
> You can change the in-ROM game name using the highlighted textbox, but it is only useful if you plan to add more AGI games to the same ROM,

> [!TIP]
> GBAGI will boot directly into the game if there is only one game in the rom.

> [!NOTE]
> If you add more than one game, the rom will boot into a simple menu instead of directly into the game.
> The names from step 5 is used for the menu entries.


> [!TIP]
> My advice is to make 1 romfile per game
> it makes it easier to find and avoids any potential savestate issues or similar.

> [!TIP]
> If you're going to burn the rom onto chips to be used on a real cartridge, then it makes more sense to have multiple games available on one cart.
 
**6) Injecting the AGI game(s) into GBA roms**

![Injecting Games](https://github.com/user-attachments/assets/2fa3c65d-7b26-41ed-a749-e21e0faee8df)

The game chosen in step 4 should now show up in the **Games To Inject** field of gbinject.

> [!IMPORTANT]
> If you want to add more AGI games to this ROM, stop here, go back and and repeat the process from step 4.
> 
> When you are finished adding games, continue below)

When you have added the game(s) you want to port,
Press **[Build ROM]**
 
**7) Conglaturatons, your winer!**

![Success](https://github.com/user-attachments/assets/74e0986c-1d4e-4d84-8ae9-3f505e0dcb33)

You now have one or more GBA ROMfile(s) with AGI game(s) ready to be played on emulators, fpga and/or real hardware using a flashcart etc.

![GBA rom](https://github.com/user-attachments/assets/1b3c7eaf-6bb3-47be-944b-cfacb4759f6c)

### Where?

[Download Brandon Kouri's AGI DeMake of Kings Quest VI here](https://kq6agi.com)

[Download Davidebyzero's updated and fixed GBAGI here](https://github.com/Davidebyzero/GBAGI)

</details>

<details>
<summary> Sierra Demo Packs  </summary>

Demos are publicly hosted on archive.org 

[Download Sierra Agi Demo Pack #1 here] (https://archive.org/details/SierraAgiDemoPack1)

[Download Sierra Agi Demo Pack #2 here] (https://archive.org/details/SierraAgiDemoPack2)

[Download Sierra Agi Demo Pack #3 here] (https://archive.org/details/SierraAgiDemoPack3)

[Download Sierra Agi Demo Pack #4 here] (https://archive.org/details/SierraAgiDemoPack4)

[Download Sierra Agi Demo Pack #5 here] (https://archive.org/details/SierraAgiDemoPack5)
</details> 

#### List of Official Sierra AGI Games
<details>
<Summary> Show List and Links </Summary>

Game names links to storepage on GOG.com (if available)
> GOG.com only sell these games in bundles.
> With the exception of Kings Quest 1-3, the linked bundles also includes games that are not AGI (But all games are well worth owning and playing)

● [King’s Quest I: Quest for the Crown](https://www.gog.com/en/game/kings_quest_1_2_3)

● [King’s Quest II: Romancing the Throne](https://www.gog.com/en/game/kings_quest_1_2_3)

● [King’s Quest III: To Heir Is Human](https://www.gog.com/en/game/kings_quest_1_2_3)

● [King’s Quest IV: The Perils of Rosella](https://www.gog.com/en/game/kings_quest_4_5_6)

● [Space Quest I: The Sarien Encounter](https://www.gog.com/en/game/space_quest_1_2_3)

● [Space Quest II: Vohaul’s Revenge](https://www.gog.com/en/game/space_quest_1_2_3)

● [Leisure Suit Larry in the Land of the Lounge Lizards](https://www.gog.com/en/game/leisure_suit_larry) 

● [Police Quest: In Pursuit of the Death Angel](https://www.gog.com/en/game/police_quest_1_2_3_4)

● The Black Cauldron 

● Mixed-Up Mother Goose 

● Gold Rush! 

● Manhunter: New York 

● Manhunter 2: San Francisco

■ [Source](https://en.wikipedia.org/wiki/Adventure_Game_Interpreter) 
</details>

### Huh?
** Helpful Useful Hints for Playing Kings Quest VI AGI on GBA: **

> [!TIP] 
> **Controls**
> 
> **+ Dpad** moves Alexander around
> 
> **(A)** Button opens the word menu
> 
> **(B)** Button deletes word and cancels
> 
> **(START)** Button opens the on-screen Keyboard (for pressing keys required by the game) and pressing **[ESC]** will open the top game settings menu
>
> **(SELECT)** Button Will scroll the screen downwards for the first two presses, and on the third press, it scrolls the screen upwards, back to the top.

> [!TIP] 
> Save often!,
> use the in-game save feature and/or savestates frequently

> [!CAUTION]
> Some Hints May Contain minor or major Spoilers!
> Spoilers should be hidden until you choose to reveal them

> [!TIP]
> **What's with this moveable arrow?**
> In close up views and when climbing the Cliffs of Logic, you'll get a sort of "point-and-click" interface where you can control a arrow around.
> the tip of the arrow is where clicks are registered.
<details>
<summary>For example in close up views: </summary>
to pick up the coin in the chest, move the arrow so the tip is on the coin.
</details>

<details>
<summary>Example when climbing the Cliffs: </summary>
position the tip of the arrow within the darker area of the "steps"
</details>

> [!WARNING]
> this next entry reveals parts of the endgame!
> Only reveal it if your clicks are not registering.
> (or if you don't care about spoilers)

<details>
<summary> **ENDGAME CLICKS DOESN'T WORK !HEAVY SPOILERS!** </summary>
When confronting The Vizier, first click on the sword on the wall next to you.
the arrow turns into a big sword, again the tip is where it registers clicks.
for the final blow, you may not be able to click on the vizier, it seems some timings/locations are off, so the vizier might not actually be where the game shows his character.
</details>


> [!TIP]
> **Suddenly Parser input?**
> In some cases you are required to enter a number or some text (for example selecting islands on the map or answering a riddle)
> this is accomplished by pressing up and down to scroll between letters A-Z and numbers 0-1 (scrolling letters wraps around) then pressing right once on the Dpad to go to the next character to be entered (left moves back to the previous character) and blank means space, and numbers may nees to be padded with zeros.

<details>
<summary> For Example </summary>
The map asks for a 3 digit number to select island 1 through 5, so to go to island 3, enter 003)
</details>


> [!TIP] 
> ** Cut off View? **
> since the GBA screen is a different aspect and resolution to what the game originally puts out on PC, 
> you might find some text and graphics at the bottom of the screen is "missing".
 
<details>
<summary> For Example </summary> this is very evident when reading the Spellbook as there are three buttons on the bottom that are obscured unless you scroll the view all the way down.
</details>

> [!NOTE]
> be aware that you might not be able to change the view during a cutscene or viewing a inventory item

> [!TIP] 
> Missing Words?

● Some items that can have many names typically only have one available, and it might not always be obvious when looking at what words are available.
<details>
<summary>For example: </summary>
a "skull" is represented by the word "cranium"
</details>

● As KQ6 is originally a point and click game, some words represent the point and click action icons.
so for this game, it's better to think what you would do if you'd "point and click", instead of what you would typically write in a textparser.
<details>
<summary>For example: </summary>
"take door" is the same as "open door" as it represents using the hand on the door.
"give" can represent showing an item.
  etc.
</details>
  
● Combining items is done by selecting only the two words that the two items you are combining represent. Just like clicking an item on another item.
using more elaborate parser commands will probably fail.
<details>
<summary>For example: </summary>
"egg cranium" should combine the spoiled egg with the Skull, while "use egg cranium" is not understood by the game, 
</details>
(simpler is often better)

● When picking up some specific items, you might have to specify an item to use to pick it up with
<details>
<summary>For example: </summary>
if "take ooze" results in a "with what?" Or similar message, then you have to  add the item to collect it with, so "take ooze cup" will work.
</details>

● There are some cases where a word can represent several items, this can make it a bit confusing and frustrating when no words seem to relate to the item you want to use.
Try to find the word that's the closest to the specific item, even if it seems vague
<details>
<summary>For example: </summary>
"paper" is the closest word relating to the item "Where are you going to?" sentence at the beach of Isle of the Beast
</details>
 
 
● I have no words and I can't see!
<details>
<summary>Give me a vague hint </summary>
You're most likely trying to light the tinderbox in the catacombs after you fell from the first floor by combining words.
Try using just a single word. 
</details>

  
<details>
<summary> Just tell me straight! </summary>
You're trying to light the tinderbox in the catacombs.
Just enter "Ignite"
</details>

  

● ...but I answered the riddle correctly!?

<details>
<summary>Give me a vague hint </summary>
You're most likely trying to get into a locked room.
Try putting a blank space somewhere between. 
</details>

<details>
<summary> Just tell me straight! </summary>
You're trying to enter the treasure room by saying "ALIZEBU", try "ALI ZEBU" instead 
(add a blank space between "ALI" and "ZEBU")
</details>

### Disclaimers

> [!IMPORTANT]
> **DISCLAIMER**
> This github is not connected or related in any way to Davidebyzero and Brandon Kouri
> I am uploading this on my own
> If there is any legitimate issue with this github or any of it's contents, let me know and i will remove it
> I take no responsibility for any damaged hardware or software


> [!IMPORTANT]
> **DISCLAIMER from KQ6AGI.com:** 
> Activision holds all rights to King’s Quest. 
> This game is in no way associated with Activision. 
> It is entirely fan-made, and has been made without permission. 
> It is free of charge. 
> This work is in no way a true or accurate representation of the original Sierra On-Line application. 
> Certain application resources have been explicitly borrowed from pre-existing copyright Sierra On-Line software.
