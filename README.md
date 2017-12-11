# deep_learning_image_classifier_demo

This repository includes all the code, files for the deep learning presentation and image classification demo I gave online or offline. Enjoy.

The code and original tutorial can be found also in the tensorflow for poets: https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0 , I leveraged the code and tutorial plus some of my slides to make the demo more intuitive and fun:-) 


# Ok, let get started!

# Step 1: installation 
you need to install tensorflow and python on your computer. I highly recommend to use Linux system (e.g., Ubuntu) or MacOS, it will save you a lot of time for configration. Refer to this site: https://www.tensorflow.org/install/ to install tensorflow, *for windows, you need python 3 to run tensorflow. To install pyton, go to here:https://www.python.org/downloads/. 
if you are using linux, we can simply use native pip to install both very quickly:
Python is automatically installed on Ubuntu. Take a moment to confirm (by issuing a python -V command) that one of the following Python versions is already installed on your system:

Python 2.7
Python 3.4+
The pip or pip3 package manager is usually installed on Ubuntu. Take a moment to confirm (by issuing a pip -V or pip3 -V command) that pip or pip3 is installed. We strongly recommend version 8.1 or higher of pip or pip3. If Version 8.1 or later is not installed, issue the following command, which will either install or upgrade to the latest pip version:

$ sudo apt-get install python-pip python-dev   # for Python 2.7
$ sudo apt-get install python3-pip python3-dev # for Python 3.n
Install TensorFlow

Assuming the prerequisite software is installed on your Linux host, take the following steps:

Install TensorFlow by invoking one of the following commands:

$ pip install tensorflow      # Python 2.7; CPU support (no GPU support)
 $ pip3 install tensorflow     # Python 3.n; CPU support (no GPU support)
 $ pip install tensorflow-gpu  # Python 2.7;  GPU support
 $ pip3 install tensorflow-gpu # Python 3.n; GPU support 
 
 # Step 2: download the training pic
 in Tensorflow for poets tutorial, they use some flower pic to training,  but we are going to have some fun to train any pictures you can think of. To download a batch of pictures, the easiest way is to use Google Chrome and download pic from google image search using "Fatkun batch download image" or any other Chrome add-ons. 
 ![alt text](https://github.com/xyd945/deep_learning_image_classifier_demo/blob/master/batch_download.PNG)
 
 Save your same category pic into the same folder, name that folder wisely (e.g., name without space, I gave a bad example, but in this case, it worked). and then put those categories folder into one folder called Pic. 
 ![alt text](https://github.com/xyd945/deep_learning_image_classifier_demo/blob/master/folder_pic.PNG)
