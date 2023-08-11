# Instalación de Linux
Para poder instalar satisfactoriamente Linux es necesario que primero selecciones una distro a instalar, para esta guía utilizaremos Ubuntu como ejemplo sin embargo para todas las otras distros los pasos son muy parecidos.

1. Busca y descarga el .ISO de tu distro. En este caso como estamos instalando Ubuntu, sigue el link a su [página de descargas](https://ubuntu.com/download/desktop). Te recomendamos descargar la versión LTS (Long Term Support), pues es la versión que el equipo de Ubuntu mantendrá por varios años y es la más estable.

2. Una vez descargado el .ISO puedes utilizarlo directamente para crear una [VM (Virtual Machine)](../Instalations/Virtual_Machine.md) o crear un USB Booting Device como te mostraremos más adelante.

## Creación del Booting Device
Esta es la parte más complicada de la instalación para la mayoría de las distros introductorias. Por favor lee atentamente todos los pasos y las opciones que te aparezcan en los popups de las aplicacioenes/páginas que visitaras.

Si estas en esta sección es porque deseas instalar Linux de forma [Dual Booting](../Instalations/Dual_Booting.md) o [reemplazndo al sistema original](../Instalations/Total_System_Replacement.md). Para poder hacer esto se necesita una USB que tenga el instalador del sistema operativo a instalar, si alguna vez has instalado Windows en alguna máquina, esta USB es el equivalente al disco que había que insertar en las máquinas para instalarles Windows. Los pasos para crear esta USB (llamada USB Booting Device) varían si estás en Windows, Mac o Linux.

Es necesario que la USB que desees utilizar para volverla un Booting Device no tenga archivos que te importen, pues la conversión a un Booting Device los eliminará y no los podrás recuperar. Es importante notar que, después de la instalación, la USB puede ser regresada a su estado original y puede seguir siendo usada como cualquier USB normal, solo sigue los pasos de la sección [Regresar la USB booteable a la normalidad](#regresar-la-usb-booteable-a-la-normalidad)

## Regresar la USB booteable a la normalidad
