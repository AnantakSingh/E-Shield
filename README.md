# How to test the model

Using weapon_detection_yolov5.ipynb Jupyter notebook, uncomment the code for installing requirements and dependencies. Then run the inference using the command under the 'run inference with trained weights' section.

```
"""
Usage - sources:
    $ python ./detect.py --weights ./models/best2.pt --source 0              # webcam
                                                             img.jpg        # image
                                                             vid.mp4        # video
                                                             path/          # directory
                                                             path/*.jpg     # glob
                                                             'https://youtu.be/Zgi9g1ksQHc'  # YouTube
"""
```            
A sample video has been uploaded at runs/detect/exp3  
