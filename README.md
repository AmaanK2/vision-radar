#Vision Radar

This project attempts to calculate lane lines and information about the lead car based on two sequential input
camera frames. Special thanks to [comma.ai](https://comma.ai) for making their [openpilot](https://github.com/commaai/openpilot)
model open-source for us all to use. Also special thanks to [@littlemountainman](https://github.com/littlemountainman) 
and [@nikebless](https://github.com/nikebless) for a lot of the project code [modeld](https://github.com/littlemountainman/modeld)
, [openpilot-pipeline](https://github.com/nikebless/openpilot-pipeline).

##Instructions to run

###Run the following commands:
- Make sure to have python and pip3 installed beforehand.
- Make sure that you have a version older than python 3.10 installed since onnxruntime is not supported with the newest version of python. python 3.9 is a good option

Install the required packages:
- pip3 install onnxruntime
- pip3 install numpy
- pip3 install opencv-python
- pip3 install h5py

Run main.py:
- python3 main.py

After running the program, you should get a frame pop up with lane lines and the lead car distance approximation.

<img width="585" alt="Screen Shot 2022-05-11 at 11 20 34 AM" src="https://user-images.githubusercontent.com/82610468/167887132-8623061d-2b75-417a-8965-af45a6e217fb.png">
