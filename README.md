# XVR Trojan
 - Open the master with powershell with argument -PS for colorfull output
 - To prevent slave program to set itself to the registry open with the argument -dontallow
 - Runs on windows and it was tested on windows 10.
 - The language is C using MinGW
 - You can fix bugs and modify as much as you want, and I am learning C for quite a time and wanted to share my program.
 
 ![Alt text](image.png?raw=true "Title")
 
 Commands | Arguments | Description | Example
 -------- | --------- | ----------- | -------
 echo | {MSG} | Echo | echo Hello
 identify |  | Retrieves the computer information. |
 system | {CMD} | Executes cmd command | system ipconfig
 send_file | {SLAVE_PATH}; {MASTER_PATH} | Sends file | send_file C:\fs; D:\fm
 get_file | {SLAVE_PATH}; {MASTER_PATH} | Receivies file | get_file C:\fs; D:\fm
 keylog_clear |  | Clears keylogger data | 
 terminate |  | Stops the slave |
 exit |  | Stops the master |

# get_file subcommand
   - screenshot_small - Screenshot 30%
   - screenshot_half - Screenshot 50%
   - screenshot_full - Screenshot
   - keylogger_path - Keylogger path

# Note
 - Screenshots are saved as .ppm I use XnView to view them
