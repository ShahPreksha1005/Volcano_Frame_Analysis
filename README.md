# Volcano Frame Analysis  

## Overview  
This project extracts and analyzes frames from a volcanic activity video using computer vision techniques. It applies:  
- **Frame Extraction**: Captures individual frames for analysis.  
- **Edge Detection (Canny)**: Identifies sharp boundaries.  
- **Object Detection**: Detects significant geological structures.  
- **Image Segmentation (Watershed)**: Distinguishes magma, rock, and air pockets.  
- **Visualization**: Displays and compares original vs. processed frames.  

## Features  
- Automated frame extraction from video.  
- Edge detection to highlight volcanic structures.  
- Object detection to identify magma chambers and rock formations.  
- Image segmentation for distinguishing geological components.  
- Visual comparisons for every 50th frame.  

## Dependencies  
Install the required libraries using:  
```bash
pip install opencv-python numpy matplotlib
```  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Volcano_Frame_Analysis.git  
   cd Volcano_Frame_Analysis  
   ```  
2. Run the script with your video file:  
   ```python
   python analyze_volcano.py --video_path <your_video.mp4>
   ```  
3. The processed frames will be saved in `original_frames/` and `analyzed_frames/`.  

## Results  
- **Edge Detection**: Reveals lava flow and rock formations.  
- **Object Detection**: Highlights geological features.  
- **Segmentation**: Provides clear regions of magma and rock layers.  
- **Insights**: Frame-by-frame tracking of volcanic activity changes.  

## Future Enhancements  
- Apply deep learning for improved object detection.  
- Integrate thermal imaging data for better analysis.  
- Extend to other geological phenomena.  
