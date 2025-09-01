# Flower Recognition CNN Web App

This project is a **deep learning-based flower recognition system** built with **TensorFlow/Keras** and deployed using **Streamlit**.  
The app allows users to upload an image of a flower and get predictions across 5 categories: **daisy, dandelion, rose, sunflower, tulip**.

---

## Features

- Upload an image via the Streamlit interface  
- Classifies the image into one of five flower categories  
- Displays the predicted class and confidence score  
- Powered by a custom-trained CNN model  

---

## Tech Stack

- Python 3.9+  
- TensorFlow / Keras – Deep learning framework  
- NumPy – Numerical computations  
- Streamlit – Web app UI  

---

## Project Structure

```
📦 Flower-Recognition-App
 ┣ 📂 upload/                     # Folder for uploaded test images
 ┣ 📂 venv/                       # Virtual environment (ignored in Git)
 ┣ 📄 app.py                      # Streamlit app (UI + classification logic)
 ┣ 📓 Flower_recog_Model.ipynb    # Jupyter notebook (model training & evaluation)
 ┣ 📄 Flower_Recog_Model.h5       # Saved trained model (HDF5 format)
 ┣ 📄 Flower_Recog_Model.keras    # Saved trained model (Keras format)
 ┣ 📦 flower_photos.zip           # Dataset (archive, optional)
 ┣ 📄 requirements.txt            # Dependencies
 ┗ 📄 README.md                   # Documentation
```

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Brohan-Tech/flower-recognition-app.git
cd flower-recognition-app
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app
```bash
streamlit run app.py
```

---

## Usage

1. Open the app in your browser (default: `http://localhost:8501`)  
2. Upload an image of a flower  
3. The model will predict its category and show a confidence score  

---

## Model Training

The CNN model was trained in **`Flower_recog_Model.ipynb`** using the `flower_photos` dataset.  
The final model is saved as **`.keras`** and loaded in `app.py`.

---

## Future Improvements

- Expand to more flower categories   
- Deploy on **Streamlit Cloud / AWS / Heroku** for public access  
- Add visualization of training accuracy/loss  
- Show prediction probability distribution (bar chart)  

---
 ## Author

**Rohana Upadhyaya**    
Location: Bengaluru, Karnataka