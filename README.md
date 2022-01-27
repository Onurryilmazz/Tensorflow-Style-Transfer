# Style Transfer

Style transfer between images was performed using the VGG19 model. The necessary codes, libraries and all other information of this project are available below

|                |Files|                         |
|----------------|-------------------------------|-----------------------------|
|[style images](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/c%C4%B1gl%C4%B1k.jpg "cıglık.jpg")|`style image`                        
|[content images](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/manzara.jpg "manzara.jpg")         |`content image` 
|[result_images](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/result.png "result.png")|`result image`                        
|[source_code](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/StyleTransfer.ipynb "StyleTransger.ipynb")        |`Source Code`


## Model and Library

- Model : VGG19
- Library :
    - Tensorflow
    - PIL
    - OpenCV
    - Numpy 
    - Matplolib
    
Note : As you can see when you examine the codes, we have uploaded our model weights via the h5 file. Here is the link to download this file :
     - https://www.kaggle.com/keras/vgg19/version/1
     
## Example Input Image
![image1](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/c%C4%B1gl%C4%B1k.jpg)
![image2](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/manzara.jpg)

## Result
![result](https://github.com/Onurryilmazz/Tensorflow-Style-Transfer/blob/main/result.png)

## Research Paper
   - https://arxiv.org/pdf/1508.06576.pdf
