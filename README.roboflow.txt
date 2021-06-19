
Mask Wearing - v1 2021-06-16 10:00pm
==============================

This dataset was exported via roboflow.ai on June 16, 2021 at 3:09 PM GMT

It includes 359 images.
People are annotated in YOLO v3 Darknet format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 61 percent of the image
* Random rotation of between -5 and +5 degrees
* Random shear of between -5° to +5° horizontally and -5° to +5° vertically
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -10 and +10 percent
* Random Gaussian blur of between 0 and 1.25 pixels


