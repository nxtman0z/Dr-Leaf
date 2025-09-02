
# 🌿 **Dr-Leaf: Plant Disease Detection System**

**Dr-Leaf** is an AI-powered web application designed to detect plant diseases from leaf images using deep learning. It aims to assist farmers and agricultural professionals in early disease identification for timely intervention and healthier crops.

---

## 🧠 **Project Overview**
- **Objective**: Diagnose plant diseases via image analysis.
- **Approach**: CNN model trained on diverse plant leaf images.
- **Outcome**: Web interface to upload leaf images and get predictions.

---

## 🗂️ **Repository Structure**
```
Dr-Leaf/
├── app/
│   ├── trained_model/           # Model file goes here
│   ├── class_indices.json       # Class mappings
│   ├── main.py                  # Main web app
│   └── requirements.txt         # Python dependencies
├── model_training_notebook/     # Model training notebooks
├── test_images/                 # Sample test images
├── README.md
```

---

## 🚀 **Getting Started**

### **Prerequisites**
- Python 3.x
- Required packages in `requirements.txt`

### **Installation**
```bash
git clone https://github.com/Manish9211Ram/Dr-Leaf.git
cd Dr-Leaf
python -m venv venv
source venv/bin/activate     # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### **Model Setup**
- Download the `plant_disease_prediction_model.h5` file from the [Releases](https://github.com/Manish9211Ram/Dr-Leaf/releases) section.
- Place it inside: `app/trained_model/`

### **Run the App**
```bash
cd app
python app.py
```
Visit: [http://localhost:5000](http://localhost:5000)

---

## 🧪 **Usage**
1. Open the app in your browser.
2. Upload a clear image of a plant leaf.
3. Click **Predict**.
4. Get the disease name and confidence score.

---

## 📊 **Model Training**
- Trained on the [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease).
- Training code and process available in `model_training_notebook/`.

---

## 📁 **Model File Notice**
Due to GitHub's file size limits, the trained model (`plant_disease_prediction_model.h5`) is not stored in the repo.  
👉 **Download it from Releases and place in `app/trained_model/`.**

---

## 🤝 **Contributing**
Pull requests are welcome! Fork the repo and submit your ideas or improvements.

---

## 📄 **License**
MIT License – see the [LICENSE](LICENSE) file.

---

## 📬 **Contact**
For queries or feedback, open an issue or reach out to [Manish9211Ram](https://github.com/nxtman0z).

