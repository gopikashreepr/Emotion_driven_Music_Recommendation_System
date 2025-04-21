# 🎧 Emotion-Driven Music Recommendation System

A deep learning-based system that detects emotions from facial images using a fine-tuned **ResNet50V2** model and recommends music accordingly. This project was developed as part of our final year B.Tech project in Artificial Intelligence and Data Science.

---

## 🧠 Project Overview

- 🧑‍🤖 Uses facial expression recognition to detect emotions
- 🎵 Maps detected emotion to a music category (e.g., Pop, Acoustic, Metal)
- 🧬 Model built using **Transfer Learning (ResNet50V2)**
- 💻 Trained and tested using **FER-2013 dataset**
- 📂 Includes academic submission files, proof documents, and visuals

---

## 📂 Repository Structure

emotion-music-recommender/ 
│ 
├── base documents/ # Reference research papers 
├── paper and ppt/ # Our final research paper, report & PPT 
├── proof/ # Conference certificate, Turnitin report, confirmation mail 
├── report/ # Full report broken into multiple PDFs 
├── required images/ # Diagrams/graphs used in paper and report 
├── src/ # Source code and dataset 
              └── emotion-based-music-recommender-resnet50v2.ipynb 
└── README.md


---

## 🧪 Model Details

- Model: **ResNet50V2** (Transfer Learning)
- Framework: **TensorFlow / Keras**
- Dataset: **FER-2013** (7 emotion classes)
- Preprocessing: Image resizing, normalization
- Output: Predicted emotion mapped to a music recommendation

---

## 🎭 Emotion Classes

- Happy
- Sad
- Angry
- Disgust
- Fear
- Surprise
- Neutral

---

## 🎵 Emotion-to-Music Mapping

| Emotion  | Recommended Music Style      |
|----------|------------------------------|
| Happy    | Pop, Dance, Indie            |
| Sad      | Acoustic, Piano              |
| Angry    | Rap, Rock, Metal             |
| Neutral  | Chill, Lo-Fi, Instrumental   |
| Fear     | Calm, Nature Sounds          |
| Surprise | Electronic, Cinematic        |
| Disgust  | Ambient, Soothing tunes      |

---

## 🚀 How to Run the Project

1. Navigate to the `src/` folder
2. Open the Jupyter Notebook:  
   `emotion-based-music-recommender-resnet50v2.ipynb`
3. Install required dependencies:
   ```bash
   pip install tensorflow opencv-python matplotlib
