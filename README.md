<h1 align="center"> Arduino Algobrain Package</h1>

## *Table of contents*
 - [Introduction](https://github.com/AlgobrixCoding/Algobrain/blob/master/README.md#introduction)
 - [Prerequisites](https://github.com/AlgobrixCoding/Algobrain/blob/master/README.md#prerequisites)
 - [Algobrain Board Installation](https://github.com/AlgobrixCoding/Algobrain/blob/master/README.md#algobrain-board-installation)
 - Uploading source code
 - What's next?

## *Introduction*
This package includes :

 - **Arduino support** for the Algobrain board
 - **Compiled source code** of the Algobrain software
 - **Code examples** for using the Algobrain board
## *Prerequisites*
 - [Arduino IDE 1.69+](https://www.arduino.cc)
 - [AVRDUDESS](http://blog.zakkemble.net/avrdudess-a-gui-for-avrdude/)
 - [Algobrain Board](http://www.algobrix.com/)
 - [Micro USB](https://www.amazon.com/s?k=Micro%20USB)
## *Algobrain Board Installation*
Installing the board is very simple with just a few steps :
1. **Arduino IDE ---> File ---> Preferences ---> Additional Boards Manager URLs**
![Step 1](https://i.imgur.com/gLPYp0q.png)
2. Add the following :</br>
https://raw.githubusercontent.com/AlgobrixCoding/Algobrain/master/package_algobrain_index.json
![Step 2](https://i.imgur.com/tk5hSfY.png)
3. **Arduino IDE ---> Tools ---> Board ---> Boards Manager**
In the "Type" box search for Algobrain and install the latest version
![Step 3](https://i.imgur.com/yYPASMb.png)
## *Uploading source code*
Make sure you've [installed](https://github.com/AlgobrixCoding/Algobrain/blob/master/README.md#algobrain-board-installation) the Algobrain board.
1. Download the [compiled algobrain source code](https://github.com/AlgobrixCoding/Algobrain/tree/master/Compiled%20Algobrain).
2. Connect the Algobrain via the Micro USB.
3. Open AVRDUDESS : </br>
![AVRDUDESS](https://i.imgur.com/Q6Pxwr7.png)

![#ec1c24](https://placehold.it/15/ec1c24/000000?text=+) **Red Section :**
-- Programmer = "Arduino"
-- Port = The port connected to the Algobrain (Usually COM<??>)

![#3f48cc](https://placehold.it/15/3f48cc/000000?text=+) **Blue Section :**
-- MCU = "ATmega328PB"
-- Detect = Press this to see if the Algobrain is detected

![#0ed145](https://placehold.it/15/0ed145/000000?text=+) **Green Section :**
-- Press the "..." to select the file we want to upload.
-- "Write" should be picked
-- Format = Intel Hex

4. Press "Go" / "Program!" and wait for results.
