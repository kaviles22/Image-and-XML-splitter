# Image-and-XML-splitter
Split your jpg and xml files into train and test folders

This script will split the images that contain also an *xml* file with the same name. Example:
- image1.jpg
- image1.xml
- image2.jpg
- image2.xml
- ...

The folder containing the images should be organized this way:

Collected images<br /> 
    class1<br /> 
        - image1.jpg<br /> 
        - image1.xml<br /> 
        - image2.jpg<br /> 
        - image2.xml<br /> 
        - ...<br /> 
    class2<br /> 
        - image1.jpg<br /> 
        - image1.xml<br /> 
        - image2.jpg<br /> 
        - image2.xml<br /> 
        - ...<br /> 
    class3<br /> 
        - image1.jpg<br /> 
        - image1.xml<br /> 
        - image2.jpg<br /> 
        - image2.xml<br /> 
        - ...<br /> 
        
The destination folder will have the following structure

Splitted images
    train
    test
    
The file should be placed on the main path, initially it should look like this:
  
Main path
  Collected images
  split_images_xml.py
  
After running th file the directory will look like this:

Main path
  Collected images
  Splitted images
    - train
    - test
  split_images_xml.py
