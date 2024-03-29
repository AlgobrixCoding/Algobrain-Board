<h1 align="center">Arduino Algobrain Board Package</h1>

## *Table of contents*
 - [Introduction](https://github.com/AlgobrixCoding/Algobrain-Board#introduction)
 - [Prerequisites](https://github.com/AlgobrixCoding/Algobrain-Board#prerequisites)
 - [Algobrain Board Installation](https://github.com/AlgobrixCoding/Algobrain-Board#algobrain-board-installation)
 - [Uploading source code](https://github.com/AlgobrixCoding/Algobrain-Board#uploading-source-code)
 - [What's next? (Algorain Library)](https://github.com/AlgobrixCoding/Algobrain-Board#whats-next)

## *Introduction*
This package includes :

 - **Arduino support** for the Algobrain board
 - **Compiled source code** of the Algobrain software
 - **Code examples** for using the Algobrain board
## *Prerequisites*
 - [Download Arduino IDE 1.69 or higher](https://www.arduino.cc)
 - [Download AVRDUDESS](http://blog.zakkemble.net/avrdudess-a-gui-for-avrdude/)
 - [If you haven't bought it yet, purchase the Algobrain Board here](http://www.algobrix.com/)
 - [Micro USB is required](https://www.amazon.com/s?k=Micro%20USB)
## *Algobrain Board Installation*
Installing the board is very simple with just a few steps :
1. **Arduino IDE ---> File ---> Preferences ---> Additional Boards Manager URLs**
![Step 1](https://i.imgur.com/gLPYp0q.png)
2. Add the following :</br>
https://raw.githubusercontent.com/AlgobrixCoding/Algobrain-Board/master/package_Algobrain_index.json
![Step 2](https://i.imgur.com/tk5hSfY.png)
3. **Arduino IDE ---> Tools ---> Board ---> Boards Manager**
In the "Type" box search for Algobrain and install the latest version </br>
![Step 3](https://i.imgur.com/yYPASMb.png)
## *Uploading source code*
Make sure you've [installed](https://github.com/AlgobrixCoding/Algobrain-Board/blob/master/README.md#algobrain-board-installation) the Algobrain board.
1. Download the [compiled algobrain source code](https://github.com/AlgobrixCoding/Algobrain-Board).
To download it, press the clone or download button. Then, unzip the folder where you want it. 
2. Connect the Algobrain via the Micro USB.
3. Open AVRDUDESS : </br>
read the instructions coming after the image. 
![AVRDUDESS](https://i.imgur.com/Q6Pxwr7.png)

![#ec1c24](https://placehold.it/15/ec1c24/000000?text=+) **Red Section :**
- Programmer = "Arduino" (make sure you selected Arduino at the line under "Programmer")
- Port = The port connected to the Algobrain (Usually COM<??>)

![#3f48cc](https://placehold.it/15/3f48cc/000000?text=+) **Blue Section :**
- MCU = "ATmega328PB"
- Detect = Press this to see if the Algobrain is detected
You should see in the black screen of the AVRDUDESS, the word Detect. If you don't see, repeat the last steps. 

![#0ed145](https://placehold.it/15/0ed145/000000?text=+) **Green Section :**
- Press the "..." to select the file we want to upload.
Search for the file inside the folder you downloaded. Go to "Compiled Algobrain", then select the .HEX file type. 
- "Write" should be picked
- Format = Intel Hex

4. Press "Go" / "Program!" and wait for results.
## *What's next?*
After you feel comfortable with uploading code to your Algobrain check out the [Algobrain Library](https://github.com/AlgobrixCoding/AlgobrainLib).</br>
The Algobrain Library basically lets you use the Algobrain board's functionallity with ease.
