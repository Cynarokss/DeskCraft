# DeskCraft (English)

I translated the Spanish text into English using Google Translate since I'm not a native English speaker, so this translation is prone to errors.

DeskCraft is a terminal tool that allows you to quickly and easily create .desktop files in Linux.
Since I'm very new to programming and this application was created in a very short time, it's very error-prone, but I think it's functional.
The idea is to make it easier to create launchers without having to edit files manually.
It should work on any Linux distribution, but since I don't have the ability to test outside of my primary operating system (Arch Linux), I'm not 100% sure it will work.

## Requirements

Python 3.13+

## Installation

To install DeskCraft, simply download the release corresponding to your language (I don't know if I'll add more), unzip the downloaded file, and open a terminal. In this terminal, navigate to the path where the unzipped file is located with "cd." Once there, you have to run this command:

```
./install.sh
```

If it doesn't let you run the command, type this:

```
chmod +x install.sh
```

After you run it, you might get a message asking you to add a line to bashrc or zshrc. To quit this error, use a text editor, open that file, and paste the line. Example:

```
nano ~/.zshrc
```

If the installation went well, you can type "deskcraft" in the terminal and start using it.

## Uninstalling

To uninstall deskcraft, simply navigate to the folder where the script is located with "cd". There, run this:

```
./uninstall.sh
```

If it doesn't let you, simply type this:

```
chmod +x uninstall.sh
```

With this, the program would be uninstalled.

## How to use it?

Using it is quite simple. In a terminal, type this command:

```
deskcraft
```

A menu should open with several options. To create a . desktop, press option 1 and press Enter. Now, once that's done, you have to enter the name of the program, which will appear when you search for it. Then, it will ask you for the executable path. DO NOT use ~/ to reference home, use /home/your_username directly. There are several types of files that are commonly used as executables; the most popular, according to me, are .sh scripts and .AppImage applications, although there are probably more. Next, it will ask you for the icon. I recommend that the icon size be between 48x48 pixels and 128x128 pixels, although there is no limit. This step also asks for the path, so don't reference home with ~/, but rather /home/your_username. Then, it will ask for the category. There's no mystery here; simply enter one of the following: AudioVideo, Development, Education, Game, Graphics, Networks, Office, Science, Settings, System, or Utility. Then, it will ask for the comment, which doesn't really matter much; enter whatever you want. Then, it will ask you if you want the application to be in the terminal or not. This depends on the application you're creating a . desktop for. It's usually false, although it can also be true. And finally, it will ask you for the type of application you want; usually, it's Application.

## End

I hope you like the application. If you find any errors or have any questions, I would greatly appreciate it if you could comment so we can fix them or answer them. Have a nice day, afternoon, or night!



# DeskCraft (Español)

DeskCraft es una herramienta de terminal que te permite crear archivos .desktop en Linux de forma rápida y sencilla. 
Como soy muy novato en la programación y esta aplicación fue hecha en muy poco tiempo, está muy propensa a errores, pero creo que es funcional.
La idea es facilitar la creación de lanzadores sin tener que editar archivos a mano.
Debería funcionar en cualquier distribución de Linux, pero como no tengo la posibilidad de testear fuera de mi sistema operativo principal (Arch Linux), no estoy 100% seguro de
que funcione.

## Requisitos

Python 3.13+

## Instalación

Para instalar DeskCraft, simplemente descargas la release correspondiente a tu idioma (no se si añadire más), descomprime el archivo descargado y abre una terminal. En esta 
terminal tienes que navegar con "cd" a la ruta donde esta el archivo descomprimido. Una vez ahi, tienes que ejecutar este comando:

```
./install.sh
```

Si no te deja ejecutar el comando, pon esto:

```
chmod +x install.sh
```

Después de que lo ejecutes, posiblemente te salga un mensaje diciendo que pongan una linea en bashrc o zshrc. Para quitar este error, usa algun editor de texto y abre ese archivo, y pegas la linea. Ejemplo:

```
nano ~/.zshrc
```

Ya si la instalación salió bien, podras poner "deskcraft" en la terminal y empezar a usarlo.

## Desinstalación

Para desinstalar deskcraft, simplemente navegas con "cd" a la carpeta donde se encuentre el script. Ahi, ejecutan esto:

```
./uninstall.sh
```

Si no te deja, simplemente pones esto:

```
chmod +x uninstall.sh
```

Ya con esto, el programa estaria desinstalado.

## ¿Como usarlo?

Usarlo es bastante simple. En una terminal, pon este comando:

```
deskcraft
```

te deberia abrir un menú con varias opciones, para crear un .desktop, pulsas la opción 1 y le das enter. Ahora, una vez puesto eso, tienes que poner el nombre del programa, el que aparecera cuando lo busques. Luego, les pedira la ruta del ejecutable, NO uses ~/ para referenciar home, hazlo directamente con /home/tu_usuario. Hay varios tipos de archivos que se suelen usar de ejecutables, los más populares, según yo, son scripts .sh y aplicaciones .AppImage, aunque seguramente hayan más. Luego te pedira el icono, de icono recomiendo que tenga de 48x48 pixeles a 128x128 pixeles, aunque no hay limite. En este paso también te pide la ruta, asi que igualmente no referencies home con ~/, hazlo con /home/tu_usuario. Luego te pedira la categoría, aca no hay mucho misterio, simplemente es poner una de las siguientes: AudioVideo, Development, Education, Game, Graphics, Networks, Office, Science, Settings, System, Utility. Luego te pedira el comentario, que realmente no importa mucho, pon lo que quieras. Luego te pedira si quieres que la aplicación sea en terminal o no, esto depende la aplicación a la cual le estas haciendo .dekstop, mayoritariamente es false aunque también puede ser true. Y por ultimo, te pedira que pongas que tipo de aplicación quieres, normalmente es Application. 

## Final

Espero que les guste la aplicación, si encuentras algún error o tienes alguna duda, agradeceria mucho que lo comentaras para arreglarlo o responderte. ¡Que pases bien día, tarde, o noche!



