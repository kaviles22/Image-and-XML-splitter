# Image-and-XML-splitter
Split your jpg and xml files into train and test folders

This script will split the images that contain also an *xml* file with the same name. Example:
- image1.jpg
- image1.xml
- image2.jpg
- image2.xml
- ...

## Source folder
The folder containing the images should be organized this way:

- Collected images
    - class1 
        - image1.jpg
        - image1.xml
        - image2.jpg
        - image2.xml 
        - ...
    - class2<br /> 
        - image1.jpg<br /> 
        - image1.xml<br /> 
        - image2.jpg<br /> 
        - image2.xml<br /> 
        - ...<br /> 
    - class3<br /> 
        - image1.jpg<br /> 
        - image1.xml<br /> 
        - image2.jpg<br /> 
        - image2.xml<br /> 
        - ...<br /> 

## Destination folder
The destination folder will have the following structure
- Splitted images
    - train
    - test
 
The file should be placed on the main path, initially it should look like this:
- Main path 
  - Collected images
  - split_images_xml.py
  
## Final directory
After running th file the directory will look like this:

- Main path
  - Collected images
  - Splitted images 
    - train
    - test 
  - split_images_xml.py 

## Command line
python split_images_xml.py --image_folder= (*The path where all the images are stored*) --train_percentage= (*PERCENTAGE OF DATASET FOR TRAINING*)
