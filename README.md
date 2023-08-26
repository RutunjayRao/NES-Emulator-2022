NES Emulator - GameDev and Esports Club, IIT Guwahati
=============

Implemented a tailored version of the 6502 microprocessor architecture for emulating the Nintendo Entertainment System in C++.
Note- Roughly 40-50% of games should work (ie. games that use either no mapper or mappers 1, 2, 3 and experimental support for 4, 7, 66 and 11).


Screenshots
------------------------

![image](https://user-images.githubusercontent.com/63869921/189893910-baa6938a-d460-4c5f-8616-89cd0d87feaf.png)
![image](https://user-images.githubusercontent.com/63869921/189893939-c2c32cbb-06e3-4f79-9710-abc3405f8b72.png)
![image](https://user-images.githubusercontent.com/63869921/189893976-a264c2e7-3666-44fa-a733-ddc72565aa1a.png)

Controller
-----------------

Keybindings can be configured with keybindings.conf


Default keybindings:

**Player 1**

 Button        | Mapped to
 --------------|-------------
 Start         | Return/Enter
 Select        | Right Shift
 A             | J
 B             | K
 Up            | W
 Down          | S
 Left          | A
 Right         | D


**Player 2**

 Button        | Mapped to
 --------------|-------------
 Start         | Numpad9
 Select        | Numpad8
 A             | Numpad5
 B             | Numpad6
 Up            | Up
 Down          | Down
 Left          | Left
 Right         | Right


ROM files of the NES console games need to be present for the code to work.
