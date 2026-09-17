# R1CBU 1KO125
This is a custom version of Xiegu X6100 R1CBU firmware I developed for myself. Feel free to test it. Work is in progress.

This release is based on firmware R1CBU 0.34.2 by gdyuldin available here:
https://github.com/gdyuldin/x6100_gui/releases?fbclid=IwY2xjawHBQxVleHRuA2FlbQIxMAABHTASzBKB359fHWHUJV4ntpEhuHia_nrfJkARCTlbhZ-rEzBacwvXVzP3wA_aem_L9wFVayd0qkHA5YL1gTfwA

FEATURES:

Reduced font size for CW/RTTY panels in order to display 8 rows
Added CHANNELS panel
Added WEFAX decoder (still working on it, currently disabled)
HOW TO USE CHANNELS PANEL:

Press "V/M" button ON THE MICROPHONE (NOT on the transceiver!) to display custom channels list panel.
When channels panel is displayed, rotate MFK to select a channel, press MFK to tune in.
Press "Add" to create a new channel using current frequency, mode, AGC/PRE/ATT values. New channel will be added at the end of the list.
Press "Edit" to edit selected channel name
Press "Delete" to remove selected channel from the list. This action is undoable.
Press "Drag" to change position of selected channel. Button name changes to "Drop". Press "Drop" to confirm new channel position.
Press "Close" to close channels panel.
Another "quick" way to add a new channel from current frequency when channels panel is not displayed is to long press the V/M button on the microphone.

I changed the behavior of "arrow" buttons short press on the microphone: in the original R1CBU firmware they were used to increase/decrease current frequency based on current step value. On this custom firmware microphone arrow keys short press is used to quickly switch between memorized channels.
Arrow keys long press behavior has not changed.

Please note: to open channels panel or add a new channel you must use ONLY THE V/M BUTTON ON THE MICROPHONE.
The V/M button on the transceiver is still used to open the original firmware "MEM 1:1" menu.

73 DE 1KO125

You can contact me at hany@hanynet.com

Use at your own risk :)
Enjoy!

Hany El Imam
