# 🌙 Moon Surface Classification using Deep Learning

This project is my **first hands-on Deep Learning project**, where I built an **end-to-end pipeline** to classify lunar surface images into different terrain categories such as **craters, mountains, and other lunar surface features**.

The main goal of this project was to **understand how deep learning systems work in practice** — from preparing data and training a model to building a prediction pipeline and deploying it with an **API and user interface**.

While the current version focuses on **image classification**, the project can be extended in the future to **lunar crater detection using object detection models**.

---

# 🚀 Motivation

As I started learning **Deep Learning**, I wanted to build a **complete practical project rather than only studying theory**.

This project helped me understand how different components of a **machine learning system work together**, including:

- Data ingestion  
- Image preprocessing  
- Model training  
- Model evaluation  
- Prediction pipelines  
- API deployment  
- User interface for inference  

This repository represents my **learning journey and curiosity to experiment with deep learning by building real systems.**

---

# 🧠 Model

The project uses **Transfer Learning with ResNet18 from PyTorch** for image classification.

The model takes **lunar surface images as input** and predicts the terrain category.

### Example Terrain Classes

- Crater  
- Mountain  
- Other lunar surface features  

---

# 🛠 Tech Stack

The project is implemented using:

- Python  
- PyTorch  
- Torchvision  
- FastAPI  
- Streamlit  
- Pandas  
- NumPy  
- Scikit-learn  

---

The project follows a **modular machine learning pipeline structure**, where each stage of the workflow is implemented as a **separate component**.

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sakshipatole28/moon-surface-classification.git
```

### 2️⃣ Move into the project directory

```bash
cd moon-surface-classification
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🏋️ Training the Model

Run the **training pipeline**:

```bash
python -m src.pipeline.training_pipeline
```

This pipeline will:

- Download the dataset  
- Preprocess the images  
- Train the deep learning model  
- Evaluate the model  
- Save the trained model  

---

# 🔍 Running the Prediction API

Start the **FastAPI server**:

```bash
uvicorn application:application --reload
```

The API will run at:

```
http://127.0.0.1:8000
```

---

# 🖥 Running the Web Interface

Run the **Streamlit application**:

```bash
streamlit run streamlit_app.py
```

You can upload a **lunar surface image**, and the model will return the **predicted terrain class**.

---

# 📈 Future Improvements

Possible extensions for this project include:

- Converting the classification model into a **crater detection system**
- Training on **larger datasets**
- Adding **model performance visualization**
- Deploying the system to **cloud platforms**

---

# 👩‍💻 Author

**Sakshi Patole**

GitHub:  
https://github.com/sakshipatole28

---

⭐ This project reflects my **first step into deep learning** and my enthusiasm to **learn by building practical ML systems.**
