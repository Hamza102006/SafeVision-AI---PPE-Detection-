#SafeVision AI – PPE Detection

#Overview
SafeVision AI is a real-time Personal Protective Equipment (PPE) detection system designed to improve workplace safety and compliance. The system uses a YOLOv8-based computer vision model to detect hardhats, masks, safety vests, and gloves from live video streams or webcam input. It is built to support automated safety monitoring and reduce the need for manual inspections.

The project demonstrates applied computer vision, deep learning model integration, and real-time inference using Python.

#Key Features
- Real-time PPE detection from live video and webcam feeds
- Detection of multiple PPE categories including hardhats, masks, vests, and gloves
- High-performance object detection using YOLOv8
- Automated flagging of PPE non-compliance
- Designed for safety and compliance use cases aligned with OSHA, WSIB, and CSA standards

#Tech Stack
- Python
- YOLOv8
- OpenCV
- PyTorch
- NumPy
- Matplotlib
- Google Colab

#How It Works
- A YOLOv8 object detection model is loaded with pretrained or custom-trained weights.
- Video frames are captured in real time from a webcam or video file using OpenCV.
- Each frame is passed through the YOLOv8 model for inference.
- Detected PPE items are classified and drawn onto the frame with bounding boxes.
- Frames with missing required PPE are flagged as non-compliant.
- The processed video feed is displayed live with real-time annotations
