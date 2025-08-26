### PORTPROTON juegos Windows "Caribeños"

Para el disfrute de juegos caribeños en ArchLinux, la forma más comoda que se ha encontrado es usando PortProton.

Se basa en crear un almacenamiento virtual base Windows donde alojar tanto los instaladores de los juegos como las instalaciones de los mismos y posteriormente ser capaz de ejecutarlos.

![PortProton](https://flathub.org/_next/image?url=https%3A%2F%2Fdl.flathub.org%2Fmedia%2Fru%2Flinux_gaming%2FPortProton%2F55afcb2581e6d9c44e9affafe95579c1%2Fscreenshots%2Fimage-1_orig.webp&w=1200&q=75)

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

Una vez instalado, basta con ejecutar el .EXE indicandole que se desea lanzar con PortProtón. Posteriormente incluso te permite añadirlo al escritorio o a la libreria de juegos de Steam.
Además ofrece la posibilidad de usar tus lanzadores de terceros preferidos como Epic.


### MANGOHUD

![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.mm.bing.net%2Fth%2Fid%2FOIP.QPeXT7F-CeTaBMl4ACDCDQHaEK%3Fpid%3DApi&f=1&ipt=5b11b0d4c9848a4f2f61057092531f28a363fd583ee41be4cf0f60219283981b&ipo=images)

Para instalarlo:
```
sudo pacman -S mangohud lib32-mangohud gamescope
```

Para testearlo:
```
mangohud glxgears
mangohud vkcube
```

Para hacer que los juegos de Steam con PortProton lo incluyan basta con abrilos una vez con PortProton, activar ManoHud guardando la configuracion y posteriormente en Steam meter el código "mangohud %command%" dentro de las LAUNCH OPTIONS:

![PortProtonGame](Captura\ desde\ 2025-08-26\ 10-07-42.png)

![SteamGame](Captura\ desde\ 2025-08-26\ 10-58-05.png)
