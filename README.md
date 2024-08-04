CSE4076 IMAGE AND VIDEO ANALYTICS
LAB EXPERIMENT-1
#NAME: Dhaarani Pushpam S
#REG NO: 21MIA1052
link to frames: 
Lab Task 1: Setup and Basic Extraction
Objective:
Install the necessary tools and libraries, and extract frame information from a video.
Steps:
1.	Install ffmpeg and ffmpeg-python:
o	Install the ffmpeg tool and the ffmpeg-python library.
2.	Extract Frame Information:
o	Extract frame information from a sample video.
Lab Task 2: Frame Type Analysis
Objective:
Analyze the extracted frame information to understand the distribution of I, P, and B frames in a video.
Steps:
1.	Modify the Script:
o	Count the number of I, P, and B frames.
o	Calculate the percentage of each frame type in the video.
2.	Analyze Frame Distribution:
o	Plot the distribution of frame types using a library like matplotlib.
o	Plot a pie chart or bar graph showing the distribution of frame types using matplotlib.
Lab Task 3: Visualizing Frames
Objective:
Extract actual frames from the video and display them using Python.
Steps:
1.	Extract Frames:
o	Use ffmpeg to extract individual I, P, and B frames from the video.
o	Save these frames as image files.
2.	Display Frames:
o	Use a library like PIL (Pillow) or opencv-python to display the extracted frames.
Tasks:
1.	Save I, P, and B frames as separate image files using ffmpeg.
2.	Use PIL or opencv-python to load and display these frames in a Python script.
3.	Compare the visual quality of I, P, and B frames.
Lab Task 4: Frame Compression Analysis
Objective:
Analyze the compression efficiency of I, P, and B frames.
Steps:
1.	Calculate Frame Sizes:
o	Calculate the file sizes of extracted I, P, and B frames.
o	Compare the average file sizes of each frame type.
2.	Compression Efficiency:
o	Discuss the role of each frame type in video compression.
o	Analyze why P and B frames are generally smaller than I frames.
Lab Task 5: Advanced Frame Extraction
Objective:
Extract frames from a video and reconstruct a part of the video using only I frames.
Steps:
1.	Extract and Save I Frames:
o	Extract I frames from the video and save them as separate image files.
2.	Reconstruct Video:
o	Use the extracted I frames to reconstruct a portion of the video.
o	Create a new video using these I frames with a reduced frame rate.


