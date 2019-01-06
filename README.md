# Blend-transfer
A style transfer model capable of blending an alien object in an image and blend it with original image.

Model used: VGG19

## Installation Prerequisites

``` 
PyTorch, Numpy, Pandas 
```



## How to run the file

1. Click on the following link: [Google colab](https://colab.research.google.com/github/p-s-vishnu/Blend-transfer/blob/master/Blend.ipynb).

2. Upload two images the `source` (the background image with a new object) and `patch` (the background image without the object) image.

3. Modify the below line of code with the name of your `source` and `patch` image.

   ```python
   # Add source image's name below
   source_img = load_image('mix.png') 
   
   # Use patch image's name below
   patch_img = load_image('san.jpg',  shape=source_img.shape[-2:])
   ```

4. Run the code in the order of execution and finally obtain the blended image in section 6 'Display the result'.

5. Enjoy :1st_place_medal:

## Sample Output

![Blend 1](/images/blend1.png)

