# YOLOv5 Cat Detection Model

This repository contains a trained YOLOv5 model specifically designed for cat detection. The model has been trained to accurately identify and locate cats in images and video streams.

## Project Structure

- `yolov5/` - Contains the YOLOv5 framework and necessary scripts
- `yolov5s.pt` - The trained model weights file

## Requirements

- Python 3.8 or higher
- PyTorch
- OpenCV
- Other dependencies listed in `yolov5/requirements.txt`

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install the required dependencies:
```bash
cd yolov5
pip install -r requirements.txt
```

## Usage

To detect cats in an image:
```bash
python yolov5/detect.py --source path/to/image.jpg --weights yolov5s.pt
```

To detect cats in a video:
```bash
python yolov5/detect.py --source path/to/video.mp4 --weights yolov5s.pt
```

## Model Performance

The model has been trained on a dataset of cat images and is optimized for:
- Real-time detection
- High accuracy in various lighting conditions
- Different cat poses and positions

## License

This project is licensed under the MIT License - see the LICENSE file for details. 