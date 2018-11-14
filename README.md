# TIMIT_NIST_to_WAV_Processing
Converting NIST files in TIMIT to the WAV format

## Where to buy TIMIT
[TIMIT data introduction and purchase](https://catalog.ldc.upenn.edu/LDC93S1)

For this converting, you need to have sox (**SO**und e**X**change), a universal sound sample translator.

## Steps to install sox on Mac OSX

1. press **Command+Space** and type **Terminal** and press enter/return key.
2. Copy, paste and press enter/return key to run the following command on terminal: 
   **ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null**
3. Screen prompts to ask you enter password, please enter your Mac's user password to continue. 
4. Run this on terminal: **brew install sox**.

Done. You could check this out by run: **sox --help**

## Install sox on Ubuntu
run command on terminal: **sudo apt install sox**

Enjoy :)
