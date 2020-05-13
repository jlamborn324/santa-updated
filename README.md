# santa-updated
Updating code provided [here](https://www.pyimagesearch.com/2017/12/11/image-classification-with-keras-and-deep-learning/) to run correctly

## Changes

in test_network.py, the arguments "acc" and "val_acc" on lines 108 and 109 had to be changed to "accuracy" and "val_accuary"

Also, in test_network.py, the usage on line 2 was incorrect. 

The correct usage:  
  
```python test_network.py --model santa_not_santa.model --image examples/santa_01.png```  
  
After you have ran test_network.py, replace santa_01.png with any image in the examples folder and run that command to test that image 


## Installing Dependencies 
I created a requirements.txt that allows you to install all dependencies in one command. 
Download the requirements.txt and navigate into the directory containing it. The following command:  
  
```python -m pip install -r "requirements.txt"```  
  
will pip install every dependency, and skip over the ones you already have. This is useful to check if you are missing any dependencies/have outdated versions. 
