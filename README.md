# vis_2
## Visualizing what convnets learn :
###       Visualizing convnet filters :
Another easy way to inspect the filters learned by convnets is to display the visual pat-
tern that each filter is meant to respond to. This can be done with gradient ascent in
input space : applying gradient descent to the value of the input image of a convnet so as
to maximize the response of a specific filter, starting from a blank input image. The
resulting input image will be one that the chosen filter is maximally responsive to.
