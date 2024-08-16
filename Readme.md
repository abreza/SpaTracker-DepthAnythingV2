# SpaTracker with Depth Anything V2 Integration

This repository contains a Colab notebook that demonstrates the integration of SpaTracker with Depth Anything V2 for advanced video tracking and depth estimation.

## Features

- Combines SpaTracker for video tracking with Depth Anything V2 for depth estimation
- Processes video inputs to generate 2D and 3D trajectories
- Visualizes tracking results and saves them as videos
- Supports custom segmentation masks for targeted tracking

## Usage

1. Upload your video file and segmentation mask to the Colab environment.
2. Modify the `root` and `vid_name` variables to match your input files.
3. Adjust parameters such as `downsample`, `fps`, `query_frame`, and `seq_length` as needed.
4. Run the notebook cells sequentially to process your video and generate results.

## Output

The notebook generates several outputs:

- Visualized tracking results saved as a video
- Reference frame and segmentation mask images
- 2D and 3D trajectory data saved as NumPy arrays
- Original video saved in MP4 format

## Customization

You can customize the tracking and visualization parameters by modifying the following variables:

- `downsample`: Factor to downsample the input video
- `fps`: Frames per second for processing
- `len_track`: Length of track visualization
- `fps_vis`: Frames per second for output visualization
- `query_frame`: Frame to use as the query for tracking
- `point_size`: Size of points in visualization
- `seq_length`: Sequence length for tracking

## Acknowledgements

This project integrates the following works:
- [SpaTracker](https://github.com/henry123-boy/SpaTracker)
- [Depth Anything V2](https://github.com/DepthAnything/Depth-Anything-V2)
- [ZoeDepth](https://github.com/isl-org/ZoeDepth)
