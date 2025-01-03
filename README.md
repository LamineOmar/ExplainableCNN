### ExplainableCNN:
Explainable Convolutional Neural Networks (CNNs) aim to make the decision-making processes of CNNs more transparent and interpretable. Traditional CNNs are often considered "black boxes" due to their complex architectures and lack of interpretability. To address this, various methods have been developed to provide insights into their inner workings.

# 🚀 Getting Started

## 1. Install Miniconda in WSL
Run the following command to download the Miniconda installer:
```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

## 2. Create a new environment
Create a new environment with Python 3.10 using the following command:
```bash
conda create -n explain python=3.10
```

## 3. Activate the environment
Activate the newly created environment:
```bash
conda activate explain
```

## 4. Install requirements
Install the necessary dependencies using pip:
```bash
pip install -r requirements.txt
```

## 5. Run the project
To run the application, use the following command:
```bash
streamlit run app.py
```

Navigate to http://localhost:8501/ to access the application.