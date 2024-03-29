# Neural Style Transfer

The purpose of this project is to implement a neural style transfer algorithm, which refers to the process of extracting the style of one image and applying it to a content image using Convolutional Neural Networks. Here we use a pretrained 19-layer VGG to generate content and style representations. The algorithm will produce a blended image after minimizing the total loss function, which is a weighted average
of content loss and style loss. This paper further studies the impact of different parameters on the synthesized image, and the results offer great insights on what the most important factors are. We also explore applying two styles instead of one single style, producing an output image that exhibits characteristics of both styles.

The following are two examples of the output images generated by our algorithm.

<p align="left">
  <img src="https://github.com/xhqkatrina/Neural_Style_Transfer/blob/master/example_1.PNG" width="256">
  <img src="https://github.com/xhqkatrina/Neural_Style_Transfer/blob/master/example_2.PNG" width="256">
</p>

For more details, please refer to our report and code implementation.
