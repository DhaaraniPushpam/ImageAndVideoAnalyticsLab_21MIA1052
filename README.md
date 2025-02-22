# Video Frame Analysis

This repository contains a collection of tasks focused on video frame extraction, analysis, and visualization using Python and ffmpeg.

## Lab Tasks

### Lab Task 1: Setup and Basic Extraction
**Objective:** Install the necessary tools and extract frame information from a video.

#### Steps:
1. **Install ffmpeg and ffmpeg-python**
   - Install the ffmpeg tool and the ffmpeg-python library.
2. **Extract Frame Information**
   - Extract frame information from a sample video.

### Lab Task 2: Frame Type Analysis
**Objective:** Analyze extracted frame information to understand the distribution of I, P, and B frames in a video.

#### Steps:
1. **Modify the Script**
   - Count the number of I, P, and B frames.
   - Calculate the percentage of each frame type in the video.
2. **Analyze Frame Distribution**
   - Plot the distribution of frame types using matplotlib.
   - Create a pie chart or bar graph to visualize the distribution.

### Lab Task 3: Visualizing Frames
**Objective:** Extract and display individual frames using Python.

#### Steps:
1. **Extract Frames**
   - Use ffmpeg to extract I, P, and B frames as images.
2. **Display Frames**
   - Use PIL (Pillow) or OpenCV to display the extracted frames.

#### Tasks:
- Save I, P, and B frames separately.
- Load and display frames using PIL or OpenCV.
- Compare the visual quality of frame types.

### Lab Task 4: Frame Compression Analysis
**Objective:** Analyze the compression efficiency of different frame types.

#### Steps:
1. **Calculate Frame Sizes**
   - Compute file sizes of I, P, and B frames.
   - Compare the average sizes of each frame type.
2. **Compression Efficiency**
   - Discuss the role of each frame type in video compression.
   - Explain why P and B frames are typically smaller than I frames.

### Lab Task 5: Advanced Frame Extraction
**Objective:** Extract and reconstruct a video using only I frames.

#### Steps:
1. **Extract and Save I Frames**
   - Extract and save I frames separately.
2. **Reconstruct Video**
   - Recreate a portion of the video using only I frames.
   - Generate a new video at a reduced frame rate.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/video_frame_analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd video_frame_analysis
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Run the scripts for each lab task as needed.
- Analyze the extracted data and frame distributions.

## License
This project is licensed under the MIT License.

## Author
Dhaarani Pushpam S

