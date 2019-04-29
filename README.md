# This keyboard layout transformation pack will help UE users to quickly switch to the US layout without changing keyboard 
The main use case would be for coding and maybe also any activites that relies on lot of english writting. 

## Before / After

## Requirements 
- MacOS 10.2 or higher 
- An ISO/IEC 9995 keyboard (Any European keyboard should be fine)
- A printer for printing the key labels (Or a pencil/paper for drawing)
- Single-sided tape 
- Souble-sided tape

## Tutorial

**Install & use the layout: **

- Open a new terminal (COMMAND + SPACE then type terminal then type enter)
- Then enter this : git clone https://github.com/MarcFaussurier/EU-to-US-keyboard-layout.git && cd EU-to-US-keyboard-layout 
- To install the layout : sudo cp Keyboard\ Layouts/* ~/Library/Keyboard\ Layouts 
- To use the layouts : press COMMAND + SPACE then type keyboard and press enter 
- Go to input source, click the plus "+" symbol at the bottom of the window 
- Go to "others" tab qnd choose ue-to-us then click "add"
- Now to use it, click on the flag to the top-right corner of your screen to switch your layout 

**Change your keyboard keys labels: **

## Credits / Tools used  
- Ukelele (http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) and VIM for layout creation 
- Cameron Lowell Palmer for his tutorial about .icns icons linking with a keyboard layout, see https://superuser.com/a/814371 
- Mathias Bynens for the space bar key (As I was unable to make it working with Uklele I copied the key from here https://github.com/mathiasbynens/custom.keylayout/blob/master/azerty/azerty.keylayout)

## License
GPLv3
