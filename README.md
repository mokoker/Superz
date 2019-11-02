A repo for super resolution using basic neural networks.

Super resoltion is an ill posed problem that doesn't have a unique answer a low resolution image(lr) can correspond to multiple high resolution(hr) images. Specially in over x4 resolution there are lots of lost information, many textures are lost, a gray are in a lr image can actually have a pattern there and it is imposible to know that information.

low resolution image

![low](https://github.com/mokoker/Superz/blob/master/figures/onelayerlow.png)

resolution increased with one layer network

![regenerated with one layer](https://github.com/mokoker/Superz/blob/master/figures/onelayerregen.png)

resolution increased with two layer network

![regen 2 layers](https://github.com/mokoker/Superz/blob/master/figures/2layer5kernelregen.png)

original high res image

![original](https://github.com/mokoker/Superz/blob/master/figures/onelayeroriginal.png)

car low res image

![carlow](https://github.com/mokoker/Superz/blob/master/figures/carlow.png)

car regenerated

![regen](https://github.com/mokoker/Superz/blob/master/figures/carregenx4.png)

car original

![original](https://github.com/mokoker/Superz/blob/master/figures/carhigh.png)


***

16x super resolution from 40x40 to 160x160

low res

![16low](https://github.com/mokoker/Superz/blob/master/figures/16x2low.png)

regenerated 

![regen1](https://github.com/mokoker/Superz/blob/master/figures/x164layer.png)

regenerated 2

![regen 2](https://github.com/mokoker/Superz/blob/master/figures/16x2regen2.png)

original 

![original](https://github.com/mokoker/Superz/blob/master/figures/16x2original.png)

supermoviechunks notebook scales a full hd movie to a 4k movie. Here are 3 screens from blade runner model(selected ones with problems try to find them :))

full hd image
![bladerunner low](https://github.com/mokoker/Superz/blob/master/figures/330lo.jpg)

4k upscaled image
![bladerunner high](https://github.com/mokoker/Superz/blob/master/figures/330x.jpg)

full hd image
![bladerunner low](https://github.com/mokoker/Superz/blob/master/figures/379lo.jpg)

4k upscaled image
![bladerunner high](https://github.com/mokoker/Superz/blob/master/figures/379x.jpg)

full hd image
![bladerunner low](https://github.com/mokoker/Superz/blob/master/figures/409lo.jpg)

4k upscaled image
![bladerunner high](https://github.com/mokoker/Superz/blob/master/figures/409x.jpg)
