This payload extracts the first 4 WiFi network profiles from the device, as well as their passwords. This information is then stored in a file in the home folder called 'pass.txt'. The contents of 'pass.txt' are then saved in a variable and converted using a series of commands, then sent to the specified webhook. After sending it, the 'pass.txt' file is deleted and the PowerShell history is cleared. Finally, the terminal is closed.

If your device correctly adjusts to the DELAY times I have set, it should take approximately 10 seconds to complete the entire process.

This payload is designed by default for Windows devices with the operating system language set to Spanish, in case it is in another language, you will need to make the changes indicated below.
