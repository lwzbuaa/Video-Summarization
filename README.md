Efficient CNN based summarization of surveillance videos for resource-constrained devices
==================
Paper
=========
https://www.sciencedirect.com/science/article/pii/S0167865518303842

Repository Details
=========
This repository contains two root folders: 1) VS-Python and 2) VS-Matlab. This paper has been implemented in both these languages.

VS-Python (1)
=======
The python implementation of this paper has some prerequisites that are necassary for running the code.
The two most important dependencies are: OpenCV >= 3.4 and Caffe (deep learning framework).

OpenCV can be easily installed by following the below links:
- https://jeanvitor.com/cpp-opencv-windonws10-installing/
- https://docs.opencv.org/3.4.3/d3/d52/tutorial_windows_install.html

These are links for pre-built OpenCV libraries.

Caffe building is a little bit hard and you need to follow up a straight forward tutorial from YouTube. 

Here is the official caffe installation page, which you may find hard to follow, but do not worry I will also share a tutorial link
- https://caffe.berkeleyvision.org/installation.html
- https://github.com/BVLC/caffe/tree/windows

Here is the YouTube link:

- https://www.youtube.com/watch?v=nrzAF2sxHHM

Furthermore, you need to install scikit-learn, tkinter, and numpy which are easy to install and can be done through just pip command.

Executing/Running the Code
=========
Running Video
- https://www.youtube.com/watch?v=deqwQ-7sumU&feature=youtu.be


Once you have all the dependencies installed and the models are downloaded, then running the code is pretty easy.

1. Open file "main.py" in any of your favourite editor [I would recommend spyder IDE]
2. Run the file "main.py" or type in command prompt "python main.py"
3. After running the program will ask you about the input video, select any video with format supported by OpenCV.
4. If everything is fine, programming will start running and will save the candidate keyframes in folder as "keyframes\temp\" (you can change the path according to your requirement
5. After this process is completed, run "postprocessing.py" which will remove redundant frames.
6. You can change the threshold for shot segmentation on line number 77 and path of the output frames at line number 88.

Downloading Caffe models (weights)
==========
Caffe models can be downloaded from the link below:

- https://drive.google.com/drive/folders/1p8M3rjWF8h5km7uyQkYaxwo0ELx4OFsb?usp=sharing


VS-Matlab (2)
=======
These codes will be uploaded soon.


Contact Me
========
Hope everything works fine for you, if there is any problem, feel free to contact me at (tanveerkhattak3797@gmail.com)


Citation
=======
<pre>
<code>
Muhammad, Khan, Tanveer Hussain, and Sung Wook Baik. "Efficient CNN based summarization of surveillance videos for resource-constrained devices." Pattern Recognition Letters (2018).
</code>
</pre>

If you are interested in Video Summarization domain you may find some of my other recent papers worthy to read:
<pre>
<code>
Hussain, Tanveer, Khan Muhammad, Amin Ullah, Zehong Cao, Sung Wook Baik, and Victor Hugo C. de Albuquerque. "Cloud-Assisted Multi-View Video Summarization using CNN and Bi-Directional LSTM." IEEE Transactions on Industrial Informatics (2019).

T. Hussain, K. Muhammad, J. D. Ser, S. W. Baik, and V. H. C. d. Albuquerque, "Intelligent Embedded Vision for Summarization of Multi-View Videos in IIoT," IEEE Transactions on Industrial Informatics, pp. 1-1, 2019.

K. Muhammad, T. Hussain, M. Tanveer, G. Sannino and V. H. C. de Albuquerque, "Cost-Effective Video Summarization using Deep CNN with Hierarchical Weighted Fusion for IoT Surveillance Networks," in IEEE Internet of Things Journal.
doi: 10.1109/JIOT.2019.2950469

K. Muhammad, H. Tanveer, J. Del Ser, V. Palade and V. H. C. De Albuquerque, "DeepReS: A Deep Learning-based Video Summarization Strategy for Resource-Constrained Industrial Surveillance Scenarios," in IEEE Transactions on Industrial Informatics.
doi: 10.1109/TII.2019.2960536
keywords: {Big Data;Computer Vision;Deep Learning;Video Summarization;IIoT;Resource-Constrained Devices},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8936419&isnumber=4389054
</code>
</pre>


