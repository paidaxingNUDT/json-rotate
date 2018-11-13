# json-rotate
You can use this code to rotate the image with the json file, and it also can rotate the corresponding json file. 
This code can expand your dataset for training.
You can follow this steps to make your own dataset for training.

# usages
1. Firstly, use the tools [labelme](https://github.com/wkentaro/labelme) to label your image data,
and it create a json file with the same name.
2. run the rotate.py file to create you dataset like Pascal Voc dataset.
Change your save path ande image.

## attention
import the utils from the tools labelme
I also rewrite the json_to_dataset from labelme/cil to fit my project.
