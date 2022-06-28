
Pistols - v4 aug2
==============================

This dataset was exported via roboflow.ai on June 25, 2022 at 1:49 PM GMT

It includes 12321 images.
Weapons are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)
* Grayscale (CRT phosphor)
* Auto-contrast via adaptive equalization

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 10 percent of the image
* Random rotation of between -10 and +10 degrees
* Random shear of between -5° to +5° horizontally and -5° to +5° vertically


