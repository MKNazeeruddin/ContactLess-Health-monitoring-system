# ContactLess-Health-monitoring-system

list of the required software and libraries to run this contactless heart 
rate monitoring project: 
Core Programming Language: 
● Python: Version 3.x (The Colab environment typically uses a recent version of 
Python 3). 
Python Libraries: 
You'll need to install the following Python libraries using pip: 
● mediapipe: Version 0.10.10 (specifically this version as indicated by the pip install 
command). This library is used for face detection in the video frames. 
● opencv-python (cv2): Used for video and image processing tasks, such as 
reading video files, resizing frames, and color space conversions. 
● numpy: Essential for numerical operations, especially for handling image and 
video data as multi-dimensional arrays. 
● matplotlib: Used for creating plots, such as displaying sample faces and 
visualizing the PPG signals and heart rate waveforms. 
● tensorflow: A powerful open-source library for numerical computation and 
large-scale machine learning. This project uses TensorFlow's Keras API to build 
and train the neural network models (LeNet, Custom CNN, GoogLeNet, UNet). 
● scikit-learn (sklearn): Provides various machine learning tools, including 
train_test_split for splitting the dataset and metrics like mean_squared_error and 
mean_absolute_error for evaluating model performance. 
● graphviz: A graph visualization software. 
● pydot: A Python interface to Graphviz, used for visualizing the architecture of the 
Keras models. You might need to install the Graphviz system software separately 
in some environments (though Colab usually has it pre-installed). 
● scipy: A library that provides tools for scientific and technical computing, 
including signal processing functionalities like find_peaks and butter (for 
Butterworth filter). 
● gradio: A library for quickly creating interactive web interfaces for machine 
learning models. It's used here to build a simple UI for uploading a video and 
getting heart rate predictions. 
Environment: 
● Google Colaboratory (Colab): The notebook is designed to run in this 
cloud-based Python environment, which provides pre-installed versions of many 
common libraries and access to GPUs or TPUs for faster training. 
How to Install (in Colab): 
Most of these libraries are likely pre-installed in a standard Google Colab environment. 
However, the notebook explicitly installs a specific version of mediapipe and you might 
need to install graphviz and pydot if they are not already available. You can install them 
by running the following commands in Colab cells: 
Python 
!pip install mediapipe==0.10.10 --no-cache-dir 
!pip install graphviz pydot 
!pip install scipy 
!pip install gradio 
Make sure to run these cells in your Colab notebook before executing the parts of the 
code that depend on these libraries. 
