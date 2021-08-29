# Plant Recognition Using Tensor Flow Object Detection Models

Model has been trained to recognize a variety of flowers. Currently recognizes Sunflowers, Daisies, and Roses.
Below is an example.
![detectedImage](https://user-images.githubusercontent.com/66883135/131268882-a1c7586c-a8d3-4d70-b3a0-0fd5501f6143.jpeg)


Adapted from Nicholas Renotte's 5-hour Youtube course on Tensor Flow object recognition. Course focused on teaching hand gestures, adapted it to recognize a variety of plants.

Currently image recognition requires the image to have a respective labelimg file.

___________________________________________________________

Resources: https://www.youtube.com/watch?v=yqkISICHH-U&ab_channel=NicholasRenotte

Coding Requirements:

Python 3.8 or higher
Tensor Flow --upgrade (2.3 currently)
Protobuf matplotlib==3.2
Numpy 1.20.0

___________________________________________________________


## Steps
<b>Step 1.</b> Create a new virtual environment inside of your respective directory
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 2.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 3.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 4.</b> Assuming images have been collected, run Plantify.ipynb, which will itself run the intialization needed through Detector.ipynb.
<br/>
<b>Step 5.</b> Your image will be saved in the same directory.
<br/>
