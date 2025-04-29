Streamlit Interactive App.
# Streamlit-2: Interactive Data Explorer 🚀

Welcome to **Streamlit-2**, a simple yet powerful Streamlit application to **upload**, **explore**, and **visualize** your data!



## 📂 Features
- Upload your own CSV file (up to 200MB)
- Instantly preview the dataset
- Navigate between:
  - **Home**
  - **Data Explorer**
  - **Visualization**
- Clean dark-themed interface
- Easy to use and extend!

---

## 🛠️ Project Structure
```bash
├── Dockerfile
├── config.toml
├── main.py
├── requirements.txt
└── README.md
```
<img width="278" alt="image" src="https://github.com/user-attachments/assets/24ddf38f-c70d-452b-88b3-0fcdc44c8fde" />


---

## 🚀 How to Run

### 1. Clone the repository
``

```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```


### 3. Run the Streamlit app
```bash
streamlit run main.py
```


---

## 🐳 Run with Docker

1. **Build the Docker image**
```bash
docker build -t streamlit2-app .
```
<img width="1013" alt="image" src="https://github.com/user-attachments/assets/2c29f700-fcbe-4003-ab0e-0d16d1ddc7fc" />


2. **Run the Docker container**
```bash
docker run -p 8501:8501 streamlit2-app
```
<img width="925" alt="image" src="https://github.com/user-attachments/assets/d427fb22-7dcc-47e9-9363-0e22c09a1b44" />


Then, open your browser and visit:  
👉 **http://localhost:8501**

<img width="1022" alt="image" src="https://github.com/user-attachments/assets/9bea7e06-df32-458d-8cec-b3ad2e24029f" />
<img width="1012" alt="image" src="https://github.com/user-attachments/assets/24a40739-d3f1-4dc0-b440-3471910ec4f0" />



---

## 📦 Requirements
- Python 3.8+
- Streamlit
- pandas

*(All listed in `requirements.txt`)*

---

## 📝 Notes
- File upload is limited to CSV format only.
- Make sure your CSV file is clean and properly formatted.
- You can extend this app easily to include charts, data cleaning, or machine learning!

---

## ✨ Acknowledgements
Built with ❤️ using [Streamlit](https://streamlit.io/).

---

## 🔗 Connect
- GitHub: [ritu-pixel](https://github.com/ritu-pixel)


![image](https://github.com/user-attachments/assets/6412aa24-a90d-4a73-bff2-8d625df79694)
