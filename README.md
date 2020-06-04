# YOLO-utility
To save the labelled annotative video 

Imagine, what if you want to look at the Object-tracked video at a later time and not at the time at which it is recorded.

Instead of relying on DARKNET framework(which does not have this functionality to save the annotative video), 
this is a custom application in python , that doesn't make use of DARKNET at all,
to save the labelled annotative video to look at it in a future time.

So, using the cfg configuration files for the models and their pretrained weights, the pyrhon script is written ,
to output the model predictions, annotate and save them in the disk.

Utility script contains functions to draw boundary box rectangles and labels on images, given that there is a detection event.
