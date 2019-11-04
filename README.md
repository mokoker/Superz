A repo for super resolution using basic neural networks. These models can upscale full hd movies to 4k(need to make them faster to run in real time)

Super resoltion is an ill posed problem that doesn't have a unique answer a low resolution image(lr) can correspond to multiple high resolution(hr) images. Specially in over x4 resolution there are lots of lost information, many textures are lost, many different textures can result to the same low resolution pattern.


16x super resolution

![comparison 16x](https://github.com/mokoker/Superz/blob/master/figures/16xcomp.png)

4x super resolution

![comparison 4x](https://github.com/mokoker/Superz/blob/master/figures/low-hi.png)

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

![comparison](https://github.com/mokoker/Superz/blob/master/figures/low-hi.png)

low res image
![jojo low](https://github.com/mokoker/Superz/blob/master/figures/15861lo.jpg)

upscaled image
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/15861gen.jpg)

high res original image
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/15861hi.jpg)

low res image
![jojo low](https://github.com/mokoker/Superz/blob/master/figures/15757lo.jpg)

upscaled image
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/15757gen.jpg)


low res image
![jojo low](https://github.com/mokoker/Superz/blob/master/figures/2713lo.jpg)

upscaled image 16x
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/2713gen.jpg)

original image
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/2713hi.jpg)

hi res original image
![jojo regen](https://github.com/mokoker/Superz/blob/master/figures/15757hi.jpg)

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

full hd image
![bladerunner low](https://github.com/mokoker/Superz/blob/master/figures/1000lo.jpg)

4k upscaled image i think this one is better than the original not just the resolution but also the colors
![bladerunner high](https://github.com/mokoker/Superz/blob/master/figures/1000x.jpg)
