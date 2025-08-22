!!!! 5€ de Aliexpress por Wifi 6 y Bluetooth 5.4 !!!!

![Dongle](https://github.com/scrakcho/BC-250/blob/1de6c73e75ef9dc020b205b83ca67de756da5aa1/configuration/AX900.jpeg)

Se necesita instalar los drivers:

```
git clone https://aur.archlinux.org/aic8800d80-dkms.git
cd rtl8851bu-dkms-git/
makepkg -si
```

Tras reiniciar, ya aparecerá la opción Wifi en el NetworkManager.

He notado que si se conecta en un puerto 2.0 la pantalla hace extraños...


