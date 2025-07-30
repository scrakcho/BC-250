## THANKS to ViRazY

![](./ViRazY_profile.png) -> Fuente de información y código original


##
This patch increases the GPU frequency range to 350 MHz - 2230 MHz, from the default 1000 MHz - 2000 MHz. This range appears to be the actual hardware limit accepted by the iGPU.

I recommend using it with https://github.com/Frogging-Family/linux-tkg, since it makes it easy to apply automatically and that kernel comes with a bunch of nice tweaks for gaming and desktop use in general. Simply create a folder called "linux612-tkg-userpatches" and place the file in there, then compile the kernel based on the instructions and press Y when it asks whether or not you want to apply it.

Keep in mind 2230 MHz requires around 1000 mv - 1050 mv based on testing and results in a good bit extra heat, so make sure your cooling solution is adequate. 
