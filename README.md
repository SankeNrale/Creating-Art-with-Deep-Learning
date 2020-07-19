# Creating-Art-with-Deep-Learning
## Neural Style Transfer
Neural style transfer is an algorithm that combines the content of one
image with the style of another image using CNN. Given a content image
and a style image, the goal is to generate a target image that minimizes
the content difference with the content image and the style difference
with the style image. 
The system uses neural representations to separate and recombine con-
tent and style of arbitrary images, providing a neural algorithm for the
creation of artistic images.

## Setup
optional:
create virtual environment
       
       virtutalenv venv
       source venv/bin/activate    
    
Local Setup:                  
                  
       Ensure that argparse, pytorch, torchvision and Pillow are installed
       (either manually, or run pip install -r requirements.txt) in the folder.
       
 ## Run the program with
       python main.py --content png/content.png --style/style.png
       
       
 ## Results
![alt text](https://github.com/sankenrale/Creating-Art-with-Deep-Learning/blob/master/result.jpg?raw=true)
