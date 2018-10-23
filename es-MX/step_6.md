## Un recorrido por la Raspberry Pi

Ahora es el momento de hacer un recorrido por la Raspberry Pi.

+ ¿Ves esa Raspberry arriba en la esquina superior izquierda? Allí es dónde accedes al menú: haz clic en él y encontrarás muchas aplicaciones.

+ Haz clic en **Accesorios (Accessories)** y elije **Editor de Texto (Text Editor)**.

![screenshot](images/pi-accessories.png)

+ Escribe `Acabo de crear un Raspberry Pi` en la ventana que aparece.

![screenshot](images/pi-text-editor.png)

+ Haz clic en **Archivo (File)**, luego elije **Guardar (Save)**, y luego haz clic en **Escritorio (Desktop)** y guarda el archivo como `rp.txt`.

![screenshot](images/pi-save.png)

+ Deberías ver aparecer un icono llamado `rp.txt` en el escritorio.

![screenshot](images/pi-saved.png)

Su archivo ha sido guardado en la tarjeta SD de la Raspberry Pi.

+ Cierra el editor de texto haciendo clic en **X** en la esquina superior derecha de la ventana.

+ Regresa al menú Raspberry, elije **Apagar (Shutdown)**, y luego elije la opción **Reiniciar (Reboot)**.

+ Cuando el Pi se haya reiniciado, tu archivo todavía debería estar allí.

+ El Raspberry Pi ejecuta una versión de un sistema operativo llamado Linux (Windows y macOS son otros sistemas operativos). El te permite "hacer que las cosas pasen" escribiendo comandos en lugar de hacer clic en las opciones del menú. Haz clic en **Terminal** en la parte superior de la pantalla:

![screenshot](images/pi-command-prompt.png)

+ En la ventana que aparece, escribe:

    ls
    

y luego presione <kbd>Enter</kbd> en el teclado.

Esto mostrará una lista de los archivos en tu `directorio de inicio (home)`.

+ Ahora escribe este comando `cd` (**c**hange **d**irectory) para ir al Escritorio (Desktop):

    cd Desktop
    

Tienes que presionar la tecla <kbd>Enter</kbd> después de cada comando.

Escribe:

    ls
    

¿Puedes ver el archivo que creaste?

+ Cierra la ventana de la terminal haciendo clic en **X**.

+ Ahora arrastra `rp.txt` a la Papelera en el escritorio para que la Raspberry Pi esté lista para la siguiente persona.
    
    ![screenshot](images/pi-waste.png)