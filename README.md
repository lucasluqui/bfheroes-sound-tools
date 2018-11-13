# bfheroes-sound-tools
Useful stuff to work with Battefield: Heroes™ sound and/or music files.

## eli5

1. find a __.wav__ file you want to convert. (mp3 files just no)
2. open a command prompt inside this folder and run any of these commands depending which task you'd like to perform:

IN-GAME SOUND (eg. weapons, bullets?)
`sox %1 -b 32 -s -c 1 -r 44100 file_name.wav`
(this one requires you to install SOX from the requirements folder)

IN-GAME AMBIENCE SOUNDS (i never tested this one actually, not guarenteed to work)
`oggenc.exe -b 112.001000 -s 0000194a %1`

LOADING MAP MUSIC
`oggenc.exe -b 112.001000 -s 00002811 %1`

FLASHMENU CLIENT MUSIC
`oggenc.exe -b 112.001000 -s 000035af %1`

3. wait for it.
4. keep waiting.
5. at this point you should have your fresh .wav/.ogg file ready to use, if you don't, get a better pc
or browse the internet for help idk.
