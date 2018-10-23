## A tour of the Raspberry Pi

Now it's time to take a tour of the Raspberry Pi.

+ See that Raspberry up in the top left-hand corner? That's where you access the menu: click on it, and you will find lots of applications.

+ לחץ על **עזרים** ובחר **עורך טקסט**.

![screenshot](images/pi-accessories.png)

+ Type `I just built a Raspberry Pi` in the window that appears.

![screenshot](images/pi-text-editor.png)

+ Click on **File**, then choose **Save**, and then click on **Desktop** and save the file as `rp.txt`.

![screenshot](images/pi-save.png)

+ אתה אמור לראות סמל בשם `rp.txt` בשולחן העבודה.

![screenshot](images/pi-saved.png)

Your file has been saved to the Raspberry Pi's SD card.

+ סגור את עורך הטקסט על ידי לחיצה על **X** בפינה הימנית העליונה של החלון.

+ Return to the Raspberry menu, choose **Shutdown**, and then choose **Reboot**.

+ When the Pi has rebooted, your file should still be there.

+ פספל פייס מפעילה גרסה של מערכת הפעלה בשם לינוקס (Windows ו- MacOS הן מערכות הפעלה אחרות). It allows you to make things happen by typing commands instead of clicking on menu options. Click on the **Terminal** at the top of the screen:

![screenshot](images/pi-command-prompt.png)

+ בחלון שמופיע, הקלד:

    ls
    

ולאחר מכן לחץ על <kbd>Enter</kbd> במקלדת.

פעולה זו תציג את הקבצים בספריה `home` שלך.

+ Now type this command to **c**hange **d**irectory to the Desktop:

    cd Desktop
    

עליך ללחוץ על המקש <kbd>Enter</kbd> לאחר כל פקודה.

Type:

    ls
    

האם אתה יכול לראות את הקובץ שיצרת?

+ סגור את חלון המסוף על ידי לחיצה על **X**.

+ Now drag `rp.txt` to the Wastebasket on the desktop so the Pi will be ready for the next person.
    
    ![screenshot](images/pi-waste.png)