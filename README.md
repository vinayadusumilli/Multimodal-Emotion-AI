# 🧠 Multimodal Emotion Recognition AI

**Multimodal-Emotion-AI** is a machine learning project that combines facial expressions and speech signals to detect human emotions. This multimodal approach enhances classification accuracy by leveraging both visual and auditory inputs.

---

## 🎯 Features

- 👁️ Facial emotion recognition using HOG + CNN (VGG16)
- 🔊 Speech emotion recognition using MFCC + LSTM
- 🧩 Multimodal fusion model for emotion classification
- 📊 Accuracy: 92% (speech), 85.7% (facial)
- 🛠 Built with TensorFlow, Keras, OpenCV, and scikit-learn

---

## 📁 Project Structure

```
Multimodal-Emotion-AI/
├── data/
│   ├── raw/                # Original datasets
│   └── processed/          # Preprocessed data
├── models/                 # Saved models
├── notebooks/              # Jupyter Notebooks for EDA and prototyping
├── src/                    # Python scripts for processing and training
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│   └── inference.py
├── demo/ 
├── app/                
│   └── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/Multimodal-Emotion-AI.git
cd Multimodal-Emotion-AI
pip install -r requirements.txt
```

---

## 🧪 Datasets

- **Facial Emotion**: [FER2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
- **Speech Emotion**: [RAVDESS](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)

---

## 🚀 Usage

### Preprocessing
```bash
python src/preprocess.py
```

### Train Models
```bash
python src/train.py --mode facial
python src/train.py --mode speech
python src/train.py --mode multimodal
```

### Evaluate
```bash
python src/evaluate.py
```

---

## 📊 Results

| Model        | Accuracy |
|--------------|----------|
| Speech Model | 92.0%    |
| Facial Model | 85.7%    |
| Combined     | 93.5%    |

---

## 📽️ Demo

<p align="center">
  <img src="demo/demo.gif" width="600"/>
</p>

---

## 💡 Future Work

- Integrate real-time webcam and microphone input
- Add multilingual and multicultural emotion detection
- Deploy using Flask

---

## 📫 Contact

Feel free to reach out:

- 📧 [vinay.adusumilli@outlook.com](mailto:vinay.adusumilli@outlook.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/vinayadusumilli)

---

_“The soul never thinks without a picture.” — Aristotle_
