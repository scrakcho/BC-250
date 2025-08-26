### PORTPROTON juegos Windows "Caribeños"

Para el disfrute de juegos caribeños en ArchLinux, la forma más comoda que se ha encontrado es usando PortProton

Se basa en crear un almacenamiento virtual base Windows donde alojar tanto los instaladores de los juegos como las instalaciones de los mismos y posteriormente ser capaz de ejecutarlos.

```
git clone https://aur.archlinux.org/portproton.git

cd portproton

makepkg -sci
```

Si usas GNOME, necesitas un extra:

```
git clone https://aur.archlinux.org/icoextract.git

cd icoextract

makepkg -sci
```

![PortProton](https://flathub.org/_next/image?url=https%3A%2F%2Fdl.flathub.org%2Fmedia%2Fru%2Flinux_gaming%2FPortProton%2F55afcb2581e6d9c44e9affafe95579c1%2Fscreenshots%2Fimage-1_orig.webp&w=1200&q=75)

Una vez instalado, basta con ejecutar el .EXE indicandole que se desea lanzar con PortProtón.
Además ofrece la posibilidad de usar tus lanzadores de terceros preferidos como Epic.

