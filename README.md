# Affective Vision

## Real-Time Facial Emotion Analytics using Deep Learning

Affective Vision is a real-time computer vision application for analyzing facial expressions from webcam streams, images, and video input using deep learning-based facial representation models.

The project integrates multiple pretrained face analysis architectures into a modular inference pipeline capable of performing live emotion detection and confidence visualization in real time.

---

## Features

- Real-time facial emotion detection
- Webcam, image, and video inference
- Support for multiple facial representation backbones
- Confidence score visualization
- Modular deep learning pipeline
- Live face detection and preprocessing
- Easy integration with Streamlit or Gradio interfaces

---

## Supported Models

- VGGFace
- FaceNet
- FaceNet512
- OpenFace
- SFace

---

## Tech Stack

- Python
- OpenCV
- TensorFlow / Keras
- Deep Learning
- Computer Vision
- Streamlit

---

## Architecture

```text
Input Image / Video Stream
            ↓
      Face Detection
            ↓
     Face Preprocessing
            ↓
   Feature Representation
            ↓
    Emotion Classification
            ↓
 Confidence Visualization
```

---

## Project Structure

```text
affective-vision/
│
├── models/
│   ├── VGGFace.py
│   ├── Facenet.py
│   ├── Facenet512.py
│   ├── OpenFace.py
│   ├── SFace.py
│
├── app/
│   └── streamlit_app.py
│
├── src/
│   ├── detector.py
│   ├── inference.py
│   ├── visualization.py
│   └── utils.py
│
├── assets/
│   ├── demo.gif
│   └── screenshots/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/affective-vision.git
cd affective-vision
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Application

### Streamlit Interface

```bash
streamlit run app/streamlit_app.py
```

---

## Example Use Cases

- Real-time webcam emotion analysis
- Human-computer interaction experiments
- AI-assisted behavioral analytics
- Interactive computer vision demos
- Emotion trend visualization

---

## Limitations

- Performance may vary under poor lighting conditions
- Facial expressions are not always reliable indicators of internal emotional state
- Accuracy may vary across demographics and camera quality
- Cultural differences can influence emotional expression

---

## Future Work

- Temporal emotion tracking across video sequences
- Multimodal emotion analysis using audio + facial signals
- Attention map visualization
- Edge-device optimization for mobile deployment
- Emotion trend analytics dashboard

---

## Demo

_Add screenshots or GIF demonstrations here._

Example:

```markdown
![Demo](assets/demo.gif)
```

---

## License

This project includes components derived from open-source facial analysis implementations released under the MIT License.

See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

This project builds upon open-source facial representation and analysis models from the computer vision research community.