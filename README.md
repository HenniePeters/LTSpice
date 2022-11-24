# My personal collection of LTSpice components

Download the zip file and unpack the directory _PERSONAL and the files it contains to:  
%USERPROFILE%\My Documents\LTspiceXVII\lib\sym\  
Unfortunately, github adds a directory named "LTSpice-master" to the zip file.  
The "_PERSONAL" directory is required because there are references to: "../sym/_PERSONAL/" in the .ASY files.  
  
Files in the _STANDARD directory can be used to replace the components in:  
%USERPROFILE%\My Documents\LTspiceXVII\lib\cmp\  
standard.bjt (1592 models)  
standard.dio (2028 models)  
standard.jft (1074 models)  
standard.mos (1632 models)  
 
The files in the _CUSTOM_SYMBOLS directory can replace the originals (without _HP in the filename).
I got irritated because I have to mirror and rotate 90 degrees every time I use the PNP or PMOS symbols.
Also RES and POLCAP have a replacement that is drawn as a European symbol.
Keep in mind that the original names are overwritten at the first update. For that reason I added the _HP in the name.

In case you have trouble using these parts, please don't hesitate to create an "issue". I really appreciate to receive feedback from other LTSpice users.
