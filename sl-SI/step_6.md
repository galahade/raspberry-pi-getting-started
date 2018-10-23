## A tour of the Raspberry Pi

Now it's time to take a tour of the Raspberry Pi.

+ See that Raspberry up in the top left-hand corner? That's where you access the menu: click on it, and you will find lots of applications.

+ Click **Accessories** and choose **Text Editor**.

![screenshot](images/pi-accessories.png)

+ Type `I just built a Raspberry Pi` in the window that appears.

![screenshot](images/pi-text-editor.png)

+ Click on **File**, then choose **Save**, and then click on **Desktop** and save the file as `rp.txt`.

![screenshot](images/pi-save.png)

+ You should see an icon named `rp.txt` appear on the desktop.

![screenshot](images/pi-saved.png)

Your file has been saved to the Raspberry Pi's SD card.

+ Close the text editor by clicking the **X** in the top right-hand corner of the window.

+ Return to the Raspberry menu, choose **Shutdown**, and then choose **Reboot**.

+ When the Pi has rebooted, your file should still be there.

+ The Raspberry Pi runs a version of an operating system called Linux (Windows and macOS are other operating systems). It allows you to make things happen by typing commands instead of clicking on menu options. Click on the **Terminal** at the top of the screen:

![screenshot](images/pi-command-prompt.png)

+ In the window that appears, type:

    ls
    

and then press <kbd>Enter</kbd> on the keyboard.

This will list the files in your `home` directory.

+ Now type this command to **c**hange **d**irectory to the Desktop:

    cd Desktop
    

You have to press the <kbd>Enter</kbd> key after every command.

Type:

    ls
    

Can you see the file you created?

+ Close the terminal window by clicking on the **X**.

+ Now drag `rp.txt` to the Wastebasket on the desktop so the Pi will be ready for the next person.
    
    ![screenshot](images/pi-waste.png)