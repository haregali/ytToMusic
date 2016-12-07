<h1>YT to Music</h1>

This is a pretty simple program mainly meant for the Raspberry PI
It uses the youtube API to find the music video then uses youtube-dl to download the video in mp3
Lastly it runs omxplayer to play the file

<h3>HOW-TO</h3>
Drop the .bashrc file and python script in your home directory(don't worry it'll only generate one other file :) )
then run play 'soundtrack title here'  NOTE: You MUST use the quotes because of the way bashrc works(or because I'm bad :P)

If it throws an error saying omxplayer doesn't exist go into bashrc using a text editor and change omxplayer to whatever player
you are using. If you have other aliases and functions in your .bashrc just copy the play function and it should still work.
