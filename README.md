# GAMING BC-250

Este repositorio ofrece información centralizada sobre el uso de esta placa.
El objetivo es brindar los datos necesarios para lograr exprimir este hardware de mineria y explotarlo para el uso Gaming.
Agradecimientos y gracias a cada una de las fuentes referidas en este documento.

## Información General
[BC250-documentation](https://github.com/mothenjoyer69/bc250-documentation) -> Repositorio con toda la información general sobre este hardware. 

## Indice
El desglose del índice que contiene esta página es el siguiente:
* [HARDWARE](https://github.com/scrakcho/BC-250/README.md/#HARDWARE)
* [BIOS](https://github.com/scrakcho/BC-250/bios/Readme.md)
* [SistemasOperativos](https://github.com/scrakcho/BC-250/README.md/#SistemasOperativos)
* [ArchLinux](https://github.com/scrakcho/BC-250/README.md/#ArchLinux)
* [Rendimiento](https://github.com/scrakcho/BC-250/evidences/Readme.md)

## HARDWARE


## SistemasOperativos
Actualmente los SO más comunes son Fedora 42, Bazzite y ArchLinux teniendo cada uno de ellos sus pros y contras.
Por ejemplo Bazzite aunque viene ya preconfigurado con todo lo necesario para tratarse como una "SteamDeck" no es nada personalizable y el uso de RAM en reposo es Moderado, por otro lado Fedora aunque es versatil no ofrece nada destacable respecto al resto y por último Archlinux, en principio, aunque requiere configuración manual se puede lograr un rendimiento mayor al resto.

<img src="https://cdn-icons-png.flaticon.com/512/3756/3756712.png" width="25" height="25">Actualmente a 21/07/2025 existe un problema con estos sistemas operativos para nuestras placas y es el uso de Kernel 6.15 el cual a metido incompatibilidades para nuestro hardware, por ello, siempre deberemos buscar una versión a usar que lleve el último kernel funciona 6.14. Se prevee que la publicación del Kernel 6.16 para finales de Julio o inicios de Agosto

## ArchLinux
* https://archlinux.org/download/ -> Página oficial de donde obtener información especifica y descargar las versiones más recientes
* https://archive.archlinux.org/iso/2025.06.01/ -> ISO de la última versión funcional para la BC-250 con Kernel 6.14
* https://github.com/eabarriosTGC/Instalacion-de-Arch-para-la-Placa-BC-250-AMD -> Guía instalación de Archlinux especifica para nuestra placa (si no se selecciona Canará y UUSS como mirrors, en el siguiente paso te fallará al no encontrar repositorios compatibles)
* https://github.com/eabarriosTGC/BC250--ARCH -> Script especifico de configuración de ArchLinux para BC-250 que incluye el Governor entre otros
* https://github.com/shahnawazshahin/steam-using-gamescope-guide -> Configuración para visualización modo GAME de SteamDeck
