# FS2020_7110.65
fixing the en_us localization pack as close to the 7110.65 as the game logic will allow

Anybody who can read the JO 7110.65 can contribute. https://www.faa.gov/air_traffic/publications/atpubs/atc_html/

Search 'ATCCOM' to find the appropriate lines.

The Microsoft Azure TTS service uses the SSML (Speech Synthesis Markup Language) as a base. Here's the place where you can insert phonemes (if syllables are molecules, phonemes are atoms). You can then use the markup to make it pronounce things correctly: for example "[p-beg]W IH N D[p-sep] Wind [p-end] {wind}" makes the right sound for "wind"- the thing that whooshes by, as opposed to what you do to a watch...

https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/speech-synthesis-markup?tabs=csharp#use-phonemes-to-improve-pronunciation
