Max 7 Patch to convert a Midi KB to the FFXIV Bard Instrument settings. Will automatically go up and down octaves by converting the Midi input to keystrokes with their modifiers. 

Requires the autobot mxj dependency, which converts the midi to keystrokes. The midi it is listening to is bound to port a
https://sites.google.com/site/theoldmanthesea/download/

The file noted "forced-timing" will push notes as fast as XIV can play them. This means if you play a chord or play notes too fast, it will add the to a queue and play them as soon as XIV is ready. To use this file, make sure to press the button labeled "press me first" before playing. 

If you do not choose the forced timing file, Max will push the note as soon as you play them, whether or not XIV is ready to play a note (Can result in dropped notes, but better timing)

-Warning- The shift/control modifiers will not reset automatically, which might result in weird behavior. If you are playing up an octave, it will continue to hold the modifier key until you press a non modified note (one that doesn't need shifted up or down in the scale). This includes if you stop playing, your computer might still think you are holding a modifier key until you press the non modified octave.


Still in alpha and may contain bugs. Please report them if you find them.
