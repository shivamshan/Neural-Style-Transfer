# Neural-Style-Transfer
Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and 
blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.</n>

This style transfer implementation makes use of the VGG-19 model and its specific layers to extract high level features that can be compared 
to a randomly generated image into some image that has the content from the **content** image and style from the **style** image.

## Initial Randomly Generated Image
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/generated.png" alt="randomly generated image">

## Content Image
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/content.jpg">

## Style Image
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/starry.jpg">

## Intermediate Images
### These images show how the intial random image develops into the final image over time
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/inter1.png">

## Final image
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/final2.png">

### Comparison
<img src="https://github.com/shivamshan/Neural-Style-Transfer/blob/master/starry1.png">

**The content and style factors can be adjusted by manipulating the alpha and beta parameters.**
