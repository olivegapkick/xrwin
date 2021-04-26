# xrwin
DOWNLOAD:
https://github.com/olivegapkick/xrwin/archive/refs/heads/main.zip


Run a batch file at loading of Windows 8 and 10
Create a shortcut to the batch file.
How to create a Windows shortcut.
Once the shortcut is created, right-click the shortcut file and select Cut.
Press Start, type Run, and press Enter.
In the Run window, type 

shell:startup 

or 

shell:common startup 


to open the Startup folder.
Once the Startup folder is opened, click the Home tab at the top of the folder. Then, select Paste to paste the shortcut file into the Startup folder.


C:\Users\USERNAME\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup




Log in with an Administrator account
Click on start and type “Task Scheduler” and hit return
Click on “Task Scheduler Library”
Click on “Create New Task” on the right hand side of the screen and set the parameters as follows:

a. Set the user account to SYSTEM

b. Choose "Run with highest privileges"

c. Choose the OS for Windows7

Click on “Triggers” tab and then click on “New…” Choose “At Startup” from the drop down menu, click Enabled and hit OK
Click on the “Actions tab” and then click on “New…” If you are running a .bat file use cmd as the program the put /c .bat In the Add arguments field
Click on “OK” then on “OK” on the create task panel and it will now be scheduled.
Add the .bat script to the place specified in your task event.
Enjoy.
