Existen MUCHAS maneras de usar Linux, y la mayor diferencia radica en DONDE quieres instalar Linux:

| Lugar 📁            | Técnica 🔨                                                    |                                                                                                                                                                                          |
| ------------------- | ------------------------------------------------------------- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Una PC completa     | [**Reemplazo del OS original**](#reemplazo-total-del-sistema) | Reemplazas el sistema operativo de tu computadora por Linux, no recomendado para principiantes pues una vez se realiza *no hay marcha atrás* :O                                          |
| Una partición de PC | [**Dual Booting**](#dual-booting)                             | Lo mejor de ambos mundos, puedes usar Linux cuando quieras sin perder tu sistema operativo original, así puedes regresar cuando gustes a tu entorno conocido.                            |
| Dentro de otro OS   | [**VM (Virtual Machine)**](#virtual-machine)                  | Consiste en emular un OS, dentro de otro. Recomendable para probar una Distro o ver de qué va esto de Linux, no la recomendamos para uso diario o prolongado por más de unos pocos días. |

# Instalación

Para poder instalar satisfactoriamente Linux es necesario que primero selecciones una distro a instalar, para esta guía utilizaremos Ubuntu como ejemplo sin embargo para todas las otras distros los pasos son muy parecidos.

1️⃣ Busca y descarga el .ISO de tu distro. En este caso como estamos instalando Ubuntu, sigue el link a su [página de descargas](https://ubuntu.com/download/desktop). Te recomendamos descargar la versión LTS (Long Term Support), pues es la versión que el equipo de Ubuntu mantendrá por varios años y es la más estable.

2️⃣ Con el .ISO descargado puedes utilizarlo directamente para crear una [VM (Virtual Machine)](#virtual-machine) o crear un USB Booting Device como te mostraremos más adelante.

## Creación del Booting Device

❗️**Importante:** Por favor lee atentamente todos los pasos y las opciones que te aparezcan en los popups de las aplicacioenes/páginas que visitaras.

Si estas en esta sección es porque deseas instalar Linux de forma [Dual Booting](#dual-booting) o [reemplazando al sistema original](#reemplazo-total-del-sistema). Para esto tendrás que tener una USB Booteable con el .ISO que quieres instalar. Los pasos para crear esta USB varían estás en Windows, Mac o Linux.

🔔**Importante:** Es necesario que la USB que desees utilizar para volverla un Booting Device no tenga archivos que te importen, pues la conversión a un Booting Device los eliminará y no los podrás recuperar. 

🔔**Importante:** Tranquilo 😁 después de la instalación, la USB puede ser regresada a su estado original y usarla como siempre, solo sigue los pasos de la sección [Regresar la USB booteable a la normalidad](#regresar-la-usb-booteable-a-la-normalidad)

Por lo general una <u>USB de 4-8GB</u> sera suficiente, busca que sea como mínimo un poco más grande que el .ISO que descargaste. <u>Para hacer tu USB Booteable existen utilizar programas como</u>:

* 🪟 **Windows**: [Rufus](https://rufus.ie/en/) es el programa que mejor nos ha funcionado, es fácil de usar aunque no es muy estético jaja.
* 🍎 **Mac**: [Balena Etcher](https://etcher.balena.io/) es un programa muy sencillo pero útil, funciona perfecto en Mac aunque en Windows es posible que no funcione.

### Balena Etcher

Para crear el disco usando [Balena Etcher](https://etcher.balena.io/) sigue los siguientes pasos:

1. Selecciona la opción "Flash from file" y selecciona el .ISO de tu distro que descargaste.
   ![Balena Etcher flash from file](resources/balena_etcher_1.png)

2. Selecciona tu USB de la lista de USB's.
   ![Balena Etcher USB list](resources/balena_etcher_2.png)

3. **Da click a FLASH!** 💥

Listo! Ya tienes una USB booting device desde la cual puedes comenzar a instalar Linux.

### Rufus

Para crear el disco usando [Rufus](https://rufus.ie/en/) sigue los siguientes pasos:

1. Selecciona el USB que quieres volver un bootable device.
   ![Rufus USB list](resources/rufus_1.png)

2. Selecciona la opción de "Disk or ISO image" y da click en el botón de "SELECT" de la derecha.
   ![Rufus ISO selection](resources/rufus_2.png)

3. Una vez seleccionada la ISO, presiona el botón de start.
   ![Rufus done](resources/rufus_3.png)

**Listo**! 💥 Tu USB se está convirtiendo en un dispositivo desde el cual puedes instalar Linux.

---

Ahora que tienes tu booting device necesitas **iniciar el proceso de instalación de Linux.** Para esto puedes ir a las secciones de [Dual Booting](#dual-booting) o [Reemplazo total del sistema](#reemplazo-total-del-sistema) las cuales necesitan de este dispositivo para funcionar.

## Dual Booting
### Crear tu particion 
El primer paso para poder hacer un dualbooting en tu pc es crear una particion en tu disco donde puedas instalar Ubuntu, para crear dicha particion debes seguir los siguientes pasos.
1. Usa el buscador de Windows e ingresa la palabra "particiones", de las opciones desplegadas elige la opcion "Crear y formatear particiones del disco. ![Imagen](./resources/DB/DB1.jpeg)
2. Cuando se despliegue la siguiente ventana, debes identificar tu disco duro (en la mayoria de computadoras se llama disco 0). ![Imagen](./resources/DB/db1.png)
3. Despues de identificar tu disco principal debes de hacer click en la seccion de mayor tamaño (en GB) y haz click derecho encima de ella, de las opciones seleccionadas elige la que tiene nombre de "reducir volumen". ![Imagen](./resources/DB/db2.png)
4. En esta ventana debes de elegir la cantidad de GB que deseas darle a tu nuevo sistema Ubuntu, lo mas recomendable es de 45GB o superior, si no sabes cuantos MB son un GB, puedes usar un conversor en linea para darle el espacio que tu desees. 
5. Este paso es solamente para algunos usuarios a los cuales no les deja poner la cantidad deseada de GB aunque si tengan esa cantidad disponible, puede que este video de como usar UltraDefrag te pueda ayudar https://www.youtube.com/watch?v=OYs8If8wIpk&t=352s.
6. Ahora que ya tienes el volumen reducido deberias de poder ver un espacio en el disco 0 con el texto "no asignado", como en la siguiente imagen.   
 ![Imagen](./resources/DB/db4.png)
7. Ya tienes tu particion creada para poder instalar tu sistema Ubuntu o la distro que tu hayas elegido.
### Entrar en la memoria booteable desde BIOS
Cuando ya hayas creado tu USB booteable siguiendo las instrucciones de [Creación del booting device](##Creación-del-Booting-Device), puedes seguir los siguientes pasos para entrar en ella y comenzar con la instalacion de Ubuntu.

1. Apaga tu PC y espera unos segundos para apretar el boton para poder entrar en tu BIOS, segun el fabricante de tu comnputadora este boton puede cambiar, para saber con exactitud cual es en tu caso puedes ver esta [pagina de ayuda](https://hanieltech.com/teclas-para-entrar-al-boot-menu/)
2. Elige el USB booteado que creaste y entra en ella.
3. Realiza la instalacion de a tu gusto hasta llegar a la parte de "Installation type".
4. Elige la opcion "Something else". ![Imagen](./resources/DB/db5.png)
5. Ahora busca la particion, la puedes identificar por su nombre, ya que aparecera como "free space".
## Virtual Machine

### Procedimiento para MacBook

Después de haber realizado lo indicado en la sección de [Instalación](#instalación) deberás seguir los siguientes pasos para poder crear tu máquina virtual.

1. Asegúrate de tener por lo menos 40 GB de espacio disponible para la instalación de la máquina virtual.
2. Dirígete a la página oficial de [UTM](https://mac.getutm.app/), después presiona el botón *Download* y espera a que se termine de descargar el archivo.
3. Cuando ya tengas el archivo descargado, dirígete a la carpeta en donde se encuentra y haz doble clic sobre él, después arrastra el icono de UTM a la sección de aplicaciones.![Imagen](./resources/VM/vm1.png)
4. Dirígete a la sección de aplicaciones y ejecuta la aplicación de UTM.![Imagen](./resources/VM/vm2.png)
5. Después de ejecutar vas a encontrarte con la siguiente interfaz.![Imagen](./resources/VM/vm3.png)
6. Haz clic en "Create a new virtual machine" y aparecerá la siguiente ventana. ![Imagen](./resources/VM/vm4.png)
7. Para el siguiente paso debes de saber el procesador de tu MacBook, si tu MacBook utiliza un procesador M1 o M2 selecciona la opción de "Virtualize", en el otro caso que son los procesadores de Intel o AMD debes de elegir la opción de "Emulate".
8. En la ventana siguiente debes de elegir la opción correspondiente a Linux.
   ![Imagen](./resources/VM/vm5.png)
9. A continuación podrás ver la siguiente ventana, asegúrate de desmarcar la casilla de "Use apple virtualization", ahora debes de presionar el botón de "Browse". ![Imagen](./resources/VM/vm6.png)
10. Después de presionar este botón se desplegará un explorador de archivos y deberás de buscar el archivo .ISO de Ubuntu o la distribución que hayas elegido.![Imagen](./resources/VM/vm7.png)
11. Presiona el botón de "open" y después el botón "continue" en la siguiente ventana.
12. Ahora asignarás los recursos necesarios a la máquina virtual. En la ventana que se desplegara deberás de asignar una cantidad de RAM para la que la máquina virtual use, en este caso se asignaran 4 GB, si tienes más RAM podrías darle una cantidad mayor. De igual manera le darás 4 núcleos y dejarás en blanco la casilla de "OpenGL acceleration". ![Imagen](./resources/VM/vm8.png)
13. En la siguiente venta le asignarás un espacio para poder almacenar el sistema y también para poder guardar los archivos con los que trabajes dentro de la máquina virtual. El espacio recomendado es más de 40 GB y en este caso le daremos 64 GB. ![Imagen](./resources/VM/vm9.png)
14. Ahora podrás hacer que una carpeta de tu sistema Mac Os pueda ser compartida con la máquina virtual, o se podrás acceder a los archivos de tu computadora desde la quina virtual. Puedes elegir cualquier carpeta o un directorio como puede ser "Downloads" en este caso. ![Imagen](./resources/VM/vm10.png)
15. Ahora solo te queda nombrar tu máquina virtual y presionar el botón "Save". ![Imagen](./resources/VM/vm11.png)
16. Para iniciar tu máquina virtual solo debes de presionar el botón "Play" que aparece en la parte superior.![Imagen](./resources/VM/vm12.png)

### Procedimiento para Windows

Para crear una máquina virtual en Windows haremos uso de “Virtual Box”, a continuación estarán todos y cada uno de los pasos para poder instalar Virtual Box y como crear tu primera máquina virtual. Antes de seguir los siguientes pasos debes saber que para poder crear una máquina virtual debes tener por lo menos 40 GB de espacio libre. 

1. Dirígete a la página oficial de Virtual Box y a su apartado de [página de descargas](https://www.virtualbox.org/wiki/Downloads).

2. Haz clic en la opción “Windows hosts” y espera a que el archivo termine de descargar.

3. Cuando el archivo esté totalmente descargado, ejecútalo y espera a hasta que la siguiente ventana aparezca.
   
    ![Imagen](./resources/VM/vw1.png)

4. Haz clic en “siguiente” y te enviará a la siguiente ventana en donde podrás personalizar la instalación de virtual box, en este caso dejaremos todo por defecto y daremos clic en next. ![Imagen](./resources/VM/vw2.png)

5. En la siguiente ventana te dará una advertencia acerca de la necesidad de reiniciar tu red durante la instalación de virtual machine, <u>asegúrate de no estar realizando ningún proceso importante en internet y ten en cuenta que deberás de esperar hasta que termine la instalación para poder seguir usando internet</u>. Al saber esto debes de dar clic en “Yes” y continuar.                
   ![Imagen](./resources/VM/vw3.png)

6. A continuación se nos dirá que se necesitan algunos otros complementos para poder instalar la máquina virtual, damos clic en “Yes” y continuamos. ![Imagen](./resources/VM/vw4.png)

7. Damos clic en Install y esperamos a que termine la instalación. ![Imagen](./resources/VM/vw5.png)

8. Cuando termine la instalación das clic en “Finish” y esperas a que se ejecute Virtual Box. ![Imagen](./resources/VM/vw6.png)

9. Al momento de ejecutar Virtual Box te encontrarás con la siguiente interfaz. ![Imagen](./resources/VM/vw7.png)

10. Para crear la máquina virtual debes ir al botón de “Nueva” y se desplegará una nueva ventana. ![Imagen](./resources/VM/vw8.png)

11. En esta nueva ventana debes de darle un nombre a la máquina virtual y puedes cambiar la ubicación donde se creara la máquina virtual. Después de darle un nombre debes de buscar el archivo .ISO que descargaste anteriormente, selecciónalo y ahora debes de asegurarte de marcar la casilla “Omitir instalación desatendida”, después haz clic en siguiente.  ![Imagen](./resources/VM/vw9.png)

12. En esta parte debes de asignar los recursos que la máquina virtual puede usar, en memoria base lo recomendable son 4 GB (si tienes más de 8 GB puedes aumentar esta cifra) y 4 núcleos (si tienes 12 núcleos o más puedes aumentar esta cifra). ![Imagen](./resources/VM/vw10.png)

13. Ahora debes de asignarle un espacio en tu disco para crear un disco virtual el cual utilizara la máquina virtual, lo recomendable es más de 40 GB, en este caso le asignaremos 64 GB, mantén la opción de “Crear un disco duro virtual ahora”. ![Imagen](./resources/VM/vw11.png)

14. Para terminar de crear la máquina virtual debes de dar clic en terminar. ![Imagen](./resources/VM/vw12.png)

15. Finalmente, para iniciar la máquina virtual, selecciona la máquina que creaste y haz clic en el botón iniciar. ![Imagen](./resources/VM/vw13.png)

Debes ir a la sección de Instalación Ubuntu para terminar con la creación de tu máquina virtual.

## Reemplazo Total del Sistema

Para instalar Ubuntu de forma que reemplaze el OS instalado dentro de nuestra computadora sigue todos los pasos para [Dual Booting](#dual-booting) con la excepción de que en el instalador seleccionarás la siguiente opción 💡:
![Instalador Ubuntu, reemplazo total del sistema](./resources/ubuntu_installer.png)

Como se puede ver en la advertencia, e<u>sta opción borrará todos los documentos y programas dentro de tu ordenador</u> y te instalara Ubuntu como si tu computadora hubiera venido con este OS por defecto en lugar de Windows/Mac.

❗️**Importante:** Una vez instalada de esta forma no hay manera de recuperar los archivos que fueron borrados durante la instalación, por lo que recomendamos que tengas una copia de seguridad antes de iniciar la instalación.

## Regresar la USB booteable a la normalidad

### Proceso en Windows

Ahora que ya hayas finalizado con la instalación del sistema Ubuntu, puedes seguir estos pasos si quieres hacer que la memoria que usaste anteriormente para instalar el sistema regrese a su estado normal. 

1. Dirígete a tu explorador de archivos y específicamente a la parte de “Este equipo”.![Imagen](./resources/VM/f1.png)
2. Una vez estés en este equipo busca el USB que usaste para “bootear” el sistema y haz clic derecho sobre él, a continuación haz clic sobre la opción “Formatear” y se desplegara la siguiente ventana.

<img src="./resources/VM/f2.png" title="" alt="Imagen" data-align="center">

3. Puedes cambiar el sistema de archivos a NTFS si lo deseas, permitira que puedas hacer más carpetas anidadas, aunque FAT32 esta más extendido.
4. Haz clic en “Iniciar” y después “aceptar” en la siguiente ventana que te aparezca, espera hasta una ventana emergente que te indique la finalización del formateo y haz clic en “aceptar” nuevamente.
5. Ahora puedes volver a usar tu USB normalmente.
