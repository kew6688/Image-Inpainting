# Image Inpainting

Try the methods from [deep image prior](https://openaccess.thecvf.com/content_cvpr_2018/html/Ulyanov_Deep_Image_Prior_CVPR_2018_paper.html) and [stable diffusion](https://huggingface.co/docs/diffusers/using-diffusers/sdxl#refine-image-quality). A comparison of a no pre-trained method and a well-trained model for image inpainting. 

Next step: Implement algorithm to automatically find watermark mask in the image.

## recover a watermark in the image: 

### Some steps in deep image prior. recover the image from a random image.
![](img/6.png) 
![](img/11.png) ![](img/10.png) ![](img/9.png) ![](img/8.png) ![](img/7.png) 

### Comparasion (Add a cat shape waterprint)
![](img/1.png) ![](img/2.png) ![](img/3.png) ![](img/4.png) ![](img/5.png) 

### Diffusion result:

![](img/diffusion.png) 

### Diffusion model can draw new object by prompt

![](img/inpaint-cat.png) 
