# Face Mask and Social Distance Detection Using Deep Learning Models

This project implements deep learning models to detect face mask usage and monitor social distancing in real-time. It is designed to assist in mitigating the spread of communicable diseases by ensuring compliance with health guidelines in crowded places such as airports, hospitals, and workplaces. This work is associated with a research paper published in Springer, accessible here: [Face Mask and Social Distance Detection Using Deep Learning Models](https://link.springer.com/chapter/10.1007/978-981-19-9819-5_34).

## Features

- **Face Mask Detection**: Identifies individuals wearing or not wearing masks with high accuracy.
- **Social Distance Monitoring**: Measures the distance between individuals and flags violations in real-time.
- **Deep Learning Models**: Utilizes MobileNet, YOLO, and ResNet-50 architectures for efficient detection.
- **Real-Time Processing**: Processes video feeds to provide immediate feedback on compliance.

## Technologies Used

- **Programming Language**: Python 3.x
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Computer Vision Library**: OpenCV
- **Development Environment**: Anaconda
- **Model Architectures**: MobileNet, YOLO, ResNet-50

## Installation & Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SaumyaGupta907/FaceMaskandSocialDistanceDetectionusingDLLmodels.git
   cd FaceMaskandSocialDistanceDetectionusingDLLmodels
   ```


2. **Set up the Anaconda environment**:

   ```bash
   conda create --name facemask_detection python=3.8
   conda activate facemask_detection
   ```


3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```


4. **Download pre-trained model weights**: Ensure that the pre-trained weights for MobileNet, YOLO, and ResNet-50 are downloaded and placed in the appropriate directories as specified in the project structure.

5. **Run the application**:

   ```bash
   python live_inference.py
   ```


   This script initiates real-time detection using your webcam.

## Usage

- **Real-Time Detection**: Execute `live_inference.py` to start the webcam feed and perform live detection of face masks and social distancing violations.

- **Training Models**: Use `train_mask_detector.py` to train the face mask detection model on a custom dataset. Ensure that your dataset is structured appropriately and the paths are updated in the script.

- **Testing**: Utilize `test_video.mp4` or any other video file to test the detection algorithms on pre-recorded footage.

## Results & Performance

The models have demonstrated high accuracy in detecting face masks and monitoring social distancing. Detailed performance metrics, including precision, recall, and F1-score, are discussed in the associated research paper.

## Research Contribution

This project is part of a research initiative aimed at leveraging deep learning for public health safety. The methodologies and findings are elaborated in the research paper published in Springer: [Face Mask and Social Distance Detection Using Deep Learning Models](https://link.springer.com/chapter/10.1007/978-981-19-9819-5_34).

## Future Enhancements

- **Integration with Surveillance Systems**: Enhance the system to integrate seamlessly with existing CCTV infrastructures.
- **Edge Deployment**: Optimize models for deployment on edge devices to enable real-time processing without reliance on cloud services.
- **Expanded Detection Capabilities**: Extend the system to detect other compliance measures, such as hand hygiene practices.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request. Ensure that your contributions align with the project's objectives and maintain code quality standards.

## Contact

- **Authors**: Saumya Gupta, N. Anusha, Y. Nikitha Naidu, M. Ruchitha & Richal Pandey 
- **LinkedIn**: [Saumya Gupta](https://www.linkedin.com/in/saumya-gupta346/)



