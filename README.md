# GAMING BC-250

Este repositorio ofrece información centralizada sobre el uso de esta placa.
El objetivo es brindar los datos necesarios para lograr exprimir este hardware de mineria y explotarlo para el uso Gaming.
Agradecimientos y gracias a cada una de las fuentes referidas en este documento.

<img src="https://cdn-icons-png.flaticon.com/512/3756/3756712.png" width="25" height="25"> En construcción


## Información General THANKS to mothenjoyer69
[BC250-documentation](https://github.com/mothenjoyer69/bc250-documentation) -> Repositorio con toda la información general sobre este hardware. 

## Indice
El desglose del índice que contiene esta página es el siguiente:
* [HARDWARE](https://github.com/scrakcho/BC-250/README.md/#HARDWARE)
* [BIOS](https://github.com/scrakcho/BC-250/blob/main/bios/Readme.md)
* [SistemasOperativos](https://github.com/scrakcho/BC-250/README.md/#SistemasOperativos)
* [ArchLinux](https://github.com/scrakcho/BC-250/README.md/#ArchLinux)
* [Rendimiento](https://github.com/scrakcho/BC-250/blob/main/evidences/Readme.md)

## HARDWARE

Se requiere como minimo una fuente de poder que entregue 220 watts en la linea de 12V aunque se recomienda como minimo de 300w para no forzarla y ocasionar reinicios que acorten la vida util de la placa. El conector es un PCI de GPU 8pin con 3 lineas de 12v y 5 GND.
Peligro al uso de adaptadores o soldaduras caseras de mala calidad.

## SistemasOperativos
Actualmente los SO más comunes son Fedora 42, Bazzite y ArchLinux teniendo cada uno de ellos sus pros y contras.
Por ejemplo Bazzite aunque viene ya preconfigurado con todo lo necesario para tratarse como una "SteamDeck" no es nada personalizable y el uso de RAM en reposo es Moderado, por otro lado Fedora aunque es versatil no ofrece nada destacable respecto al resto y por último Archlinux, en principio, aunque requiere configuración manual se puede lograr un rendimiento mayor al resto.


## ArchLinux
* [Página oficial de donde obtener información especifica y descargar las versiones más recientes](https://archlinux.org/download/) / [Listado ISOs](https://archive.archlinux.org/iso/)
* [Guía instalación de Archlinux especifica para nuestra placa](https://github.com/eabarriosTGC/Instalacion-de-Arch-para-la-Placa-BC-250-AMD)
  - si no seleccionas mirrors Canadá y UUSS, en el siguiente paso te fallará al no encontrar los repositorios necesarios
  - Si deseas automatizarlo, habilita el Bluetooth de inicio
* [Script especifico de configuración de ArchLinux para BC-250 que incluye el Governor entre otros](https://github.com/eabarriosTGC/BC250--ARCH)
* [GPU frequency range kernel patch](https://github.com/scrakcho/BC-250/blob/main/kernel/Readme.md)
* [Visor Temperaturas](https://github.com/scrakcho/BC-250/blob/main/configuration/Temp_Readme.md)
* [Configuración para visualización modo GAME de SteamDeck](https://github.com/shahnawazshahin/steam-using-gamescope-guide)
* [Optimizar cualquier juengo en ARCH Linux](https://www.youtube.com/watch?v=NOw3TPgxXYQ&ab_channel=Pingu)
