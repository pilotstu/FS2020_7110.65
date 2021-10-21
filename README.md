# FS2020_7110.65
fixing the en_us localization pack as close to the 7110.65 as the game logic will allow
Install at your own risk- only modifies the one ATC (localization file) for English (United States)

### Why github? Because anybody who can read the JO 7110.65 can contribute! See a line that should be fixed, add it as a pull request!. https://www.faa.gov/air_traffic/publications/atpubs/atc_html/

Search 'ATCCOM' to find the appropriate lines.

The Microsoft Azure TTS service uses the SSML (Speech Synthesis Markup Language) as a base. Here's the place where you can insert phonemes (if syllables are molecules, phonemes are atoms). You can then use the markup to make it pronounce things correctly: for example "[p-beg]W IH N D[p-sep] Wind [p-end] {wind}" makes the right sound for "wind"- the thing that whooshes by, as opposed to what you do to a watch...

https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/speech-synthesis-markup?tabs=csharp#use-phonemes-to-improve-pronunciation

##Changes so far
-ready for departure IFR
-radar handoff just gives altimeter (delete 'continue as planned')
-removed 'your transponder appears inoperative or malfunctioning'- instead says 'negative radar contact, reset transponder XXXX'
-switch to advisory on _ -> monitor advisory on _
-three hundred, five hundred, etc. -> tree hundred, fife hundred...
-cleared for touch and go -> cleared touch and go
-'oscar' pronunciation -> 'osca'
-'quebec' (kwabek) pronunciation -> 'kaybek'
-'clearance void thirty minutes' -> clearance void three zero minutes
-taxi to 'general aviation parking' -> taxi to 'signature' (isn't signature everywhere? lol)
-nine o'clock, three, five -> niner o'clock, tree, fife
-"good day" pronunciation-> gooday (nobody says it slowly in real life... considered changing it to CYA (line 145967)
-'decimal' -> point (the most glaring issue so far)
-proceed on course -> resume own navigation

##Install Notes
- install is just copy and paste into your main FS2020 Folder. There's a backup of the english locpak file automatically created in the community folder for Sim Update 6. If you're beyond version 1.20.6.0 (Sim Update 6), you will need to backup your en_us locpak first before installing (overwriting).
