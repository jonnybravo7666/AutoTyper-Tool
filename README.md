# AutoTyper-Tool

AutoTyper - A Data Entry Tool

Sometimes we have to write a content in programs where copy-paste is not allowed even website disable right click button or Keywords such as " ctrl C " and " ctrl V ", like in Data Entry Software or some other restricted website. There are many tools or Software available online but almost all of them are paid or they provide trial versions. And they demand big payment for continued access. And even if they are free, it is not wise to give complete access to a keyboard to any third-party software. then it will be totally dangerous and harmfull for your system i.e. why i had wrote this simple-short python script which reads content which you provide them then it simulates keyboard tyoing. This Script works with both Linux And Windows System

# Requiredment: 

Python v3

# Prerequisite:

    pip install pyautogui

# Additional Installation for Linux System

For Debain Based Systems:

    apt-get install python3-tk python3-dev

for Arch linux Based Systems:

    pacman -S tk

Parameters: 

time.sleep() -  function to allow time for the user to switch to the application they want to type in 

pyautogui.typewrite() - function to simulate typing the text "AutoTyper Tool" one character at a time with a small delay of 0.1 seconds between each keystroke.

You can modify this program to type any text you want by replacing the "AutoTyper Tool" string with your desired text. You can also adjust the delay interval to make the typing speed faster or slower depending on your needs.
