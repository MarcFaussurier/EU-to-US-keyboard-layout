# This keyboard layout transformation pack will help european users to quickly switch to the US layout without changing keyboard 
The main use case would be for coders or maybe also other activities that rely on lot of english writting. 

## Before / After

![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/clavier-macbook-azerty.jpg "Before")
![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/IMG_0206.jpg "After")


## Requirements 
- MacOS 10.2 or higher 
- An ISO/IEC 9995 keyboard (Any European keyboard should be fine)
- A printer for printing the key labels (Or a pencil/paper for drawing)
- Single-sided tape 
- Souble-sided tape

## Tutorial

**Install & use the layout:**

- Open a new terminal (COMMAND + SPACE then type terminal then type enter)
- Then enter this : git clone https://github.com/MarcFaussurier/EU-to-US-keyboard-layout.git && cd EU-to-US-keyboard-layout 
- To install the layout : sudo cp Keyboard\ Layouts/* ~/Library/Keyboard\ Layouts 
- To use the layout : press COMMAND + SPACE then type keyboard and press enter 
- Go to input source, click the plus "+" symbol at the bottom of the window 
- Go to "others" tab and choose eu-to-us then click "add"
![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/Screen%20Shot%202019-04-29%20at%2013.53.56.png "Choose layout")
- Now to use it, click on the flag to the top-right corner of your screen to switch your layout 
![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/Screen%20Shot%202019-04-29%20at%2013.54.01.png "Use layout")

- Windows keyboard users may also want to remap their alt/windows keys, to do so, COMMAND + SPACE, press keyboard then enter, click on the "Modifier Keys... " on the  right-bottom of the window to remap your alt/windows keys
![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/Screen%20Shot%202019-04-29%20at%2013.53.38.png
 "Modifier keys")

**Change your keyboard keys labels:**
- Print and/or draw the [Images/us-international-pc_1024x1024.png picture](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/us-international-pc_1024x1024.png)
- Put some double sided tape on all your keys like this: 
![alt text](https://github.com/MarcFaussurier/EU-to-US-keyboard-layout/raw/master/Images/IMG_0204.jpg "Keys placing")
- Then put your key and finally apply single sided tape for a better key texture 

## Credits / Tools used  
- Ukelele (http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) and VIM for layout creation 
- Cameron Lowell Palmer for his tutorial about .icns icons linking with a keyboard layout, see https://superuser.com/a/814371 
- Mathias Bynens for the space bar key (As I was unable to make it working with Uklele I copied the key from here https://github.com/mathiasbynens/custom.keylayout/blob/master/azerty/azerty.keylayout)
- PC4YOU for the azerty mac keyboard picture 
- bolonka-zwetna-von-der-laisbach.de for the US keyboard layout image

## License
[GPLv3](https://github.com/mathiasbynens/custom.keylayout/blob/master/azerty/LICENSE.txt)
